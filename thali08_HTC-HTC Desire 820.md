#### Test 58380500fccea7e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  907): sending alarm PendingIntent{422e6798: PendingIntentRecord{41ee7358 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70688, Int=0
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,E/cutils-trace( 4164): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4164): ====startRecUseTime====
D/htc.customization.log.level( 4164):  is 
W/CustomizationLogLevel( 4164): Level value is invalid, use default level 2
D/CustomizationManager( 4164):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4164): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4164): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4164): Parsing tag category name = system
I/CustomizationCIDLoader( 4164): Parsing tag category name = application
I/CustomizationCIDLoader( 4164): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4164): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4164): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4164): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4164): Parsing tag category name = Settings
D/CustomizationManager( 4164):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4164):  All configurations done spent 0.090 (s)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): acquireWL(4257e660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4257e660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/HtcNativeFlag( 4164): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4164): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4164): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4164): Fail to get flag for type 'language', use default value: -1
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4164
,I/CalendarProvider2( 1502): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1502): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(424bc870): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3829 10154 null
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3829): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3829): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3829, uid=10154, userID:0
I/MusicLeanback( 3829): Conditions not met for autocaching.
I/MusicLeanback( 3829): Stop autocaching.
D/PMS     (  907): releaseWL(424bc870): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4182 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4182): Loading default preferences
,W/Resources( 4182): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4182): Overriding preferences with custom values
,D/SyncApplication( 4182): Updating preferences succeeded
,E/SyncApplication( 4182): Application created.
D/VolumeInfo( 4182): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4182): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4182): Found 0 mount point(s)
,V/VolumeInfo( 4182): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4182): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4182): getNewCalendarAuthority()...
,D/VolumeInfo( 4182): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4182): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4182): enableAppOperation()+
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4182, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4182, uid=10008, userID:0
,W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4182): enableAppOperation()-
D/HTCUtilities( 4182): isNeorSinged() + 
,D/HTCUtilities( 4182): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4182): isNeorSinged() return false
,D/CDMountReceiver( 4182): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4182): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4182): enable CD Auto-mount: true
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4182): enable auto-mount
,D/HTCUtilities( 4182): enable auto-mount
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  907): Resuming delayed broadcast
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f6daa0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 2 14 12 11
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41a97bb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 1 14 3 16
,W/MediaManager( 3811): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  907): killProcessQuiet, pid=3714
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3714:com.htc.sense.news/u0a75 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  907): Recipient 3714
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4204 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=40 rxSum=37} preTxRxSum={txSum=24 rxSum=19}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19592 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19593 delay=15s
D/PMS     (  907): releaseWL(42398ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4204): onCreate
D/ProviderChangeReceiver( 4204): ---------------------------------------------------
,D/ProviderChangeReceiver( 4204): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4204): start to updateAlertNotification!
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4219 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3897
,I/ActivityManager(  907): Killing 3897:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4204): No fired or scheduled alerts
,D/HtcAlertUtils( 4204): -- cancelReminderNotification --
,D/HtcAlertUtils( 4204): broadcastExistReminder!
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiService(  907): Client connection lost with reason: 4
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3897
,V/Settings:HtcSettingsApplication( 4219): [4219/4219] onCreate()
W/ContextImpl( 4219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3643
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  907): Killing 3643:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3643
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42302f58 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 240
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 9 times.
,I/SensorManager(  907): mEventCount = 600
,D/PMS     (  907): releaseWL(4265dbd0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 264
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:73, mTXpacketCount:72, avgLinkspeed:52,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 10 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(4268ca68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{425fba90: PendingIntentRecord{4257d108 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454717615266, Int=0
,D/PMS     (  907): releaseWL(4268ca68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4054): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/AutoSetting( 1400): service - has update message, not stop
,D/AutoSetting( 1400): service - mHandler: update timezone
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1502): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1502): service - mHandler: update timezone
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz: ,
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1502): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1502): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41aa5ca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 11 4 11
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 11 times.
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 120
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 750
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=41 rxSum=38} preTxRxSum={txSum=40 rxSum=37}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19593 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19594 delay=15s
D/PMS     (  907): acquireWL(425c3cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4266b668: PendingIntentRecord{41ee7358 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87799, Int=0
D/PMS     (  907): releaseWL(425c3cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 12 times.
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:74, mTXpacketCount:73, avgLinkspeed:43,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1502): handler message = 4011
,E/HtcModeClient( 1502): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1502): Don't start project servcice
,D/HtcModeClient( 1502): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1502): connectState: CONNECTION_READY = false
,D/SilentMusic( 1502): call stop
,D/HtcModeClient( 1502): close connection
,W/HtcModeClient( 1502): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1502): read the terminate packet, so break
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425764e0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/SensorManager(  907): mEventCount = 900
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(42615e88): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(42615e88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425a72a0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(425a72a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425882b8): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(425882b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42688270): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(42688270): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/PMS     (  907): acquireWL(425b6590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=42 rxSum=39} preTxRxSum={txSum=41 rxSum=38}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19594 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19595 delay=15s
V/AlarmManager(  907): sending alarm PendingIntent{425cfbd0: PendingIntentRecord{41ee7358 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102805, Int=0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  907): releaseWL(425b6590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 192
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4243 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(426871e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{41b2ef88: PendingIntentRecord{41d044d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454717638946, Int=60000
,D/PMS     (  907): releaseWL(426871e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4243): SMSBackupAgentService started
,D/SMSBackup( 4243): Checking restore status
,D/SMSBackup( 4243): Restore complete
,D/SMSBackup( 4243): cancelCheckAlarm
,D/SMSBackup( 4243): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3873
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3873:com.htc.sdm/u0a80 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3873
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(426ee7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105362, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426ee7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1113): now=1454717640061 next=59939
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:77, mTXpacketCount:74, avgLinkspeed:43,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4214c840
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4214c840, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42302120
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@425a5580
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 371ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  907): Disable input method client, pid=1273
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42573548)
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1254): applyRouting -2
D/PMS     (  907): acquireWL(42572b50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMN     (  907): wakingUp
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(42572b50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  907): acquireWL(426dd650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2428): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting -2
,D/MtpService( 2428): [MTP][onReceive]-
I/BatteryService(  907): n_update end
D/PMN     (  907): onScreenOn
D/PMS     (  907): releaseWL(426dd650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): acquireWL(426dfe18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/PMS     (  907): releaseWL(426dfe18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1400): receiver - intent: android.intent.action.USER_PRESENT
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  907): updateBatteryInfo
D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
D/PowerUI ( 1113): closing low battery warning: level=100
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 4114): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4114): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4114): Cust_ConnectToPC   : Modem_Link>false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/        ( 4114): Cust_ConnectToPC   : spcsc>false
D/        ( 4114): Cust_ConnectToPC   : IPT>true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/        ( 4114): Cust_ConnectToPC   : Singel_USB>false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/ClockThread( 1113): stop update clock
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,W/Settings( 4114): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19596 delay=15s
,E/SmartNS_Utility( 4114): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4114): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4114): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4114): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
W/ContextImpl( 4114): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4114): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4114): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4114):  defaultType:0
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:On
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): BG scan when screen On
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): Match BG scan, scan!
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1113): WifiActivity: 0
V/NotificationService(  907): batLight: Full, plugged
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4266 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  907): updateScreenOn: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(42628fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1419 10028 null
D/PMS     (  907): releaseWL(42628fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1806): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): onScreenOn: 1454717645706
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1806): onScreenOn: 1454717645706
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42302120
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42302120, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@425a5580
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(4262b268): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/PMS     (  907): acquireWL(4262bb70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4266 1000 null
I/FeedHostManager( 1273): [onPause]
D/SmartSyncUtils( 4266): isEpsOn(), nState = 0
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fe1858
I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19596 mDataStallAlarmIntent=PendingIntent{42458298: PendingIntentRecord{41ee7358 android broadcastIntent}}
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:Off
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42632360): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(4262bb70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  907): releaseWL(4262b268): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  907): updateScreenOn: false
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(42632360): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4266): getMobilePolicyEnabled, result = true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=3566
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3566:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4266): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4266): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4266): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1240): start background delete task...
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425a5580
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425a5580, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425a5580, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425a5580
D/WifiService(  907): New client listening to asynchronous messages
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42601940 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42601940 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] getTotalRam: 1873 Mb
D/AutoSetting( 1400): service - mHandler: cancel location update
,D/AutoSetting( 1400): service -           changes count: 0
,I/ActivityManager(  907): Recipient 3566
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4273ef38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1419 10028 null
,D/PMS     (  907): releaseWL(4273ef38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1806): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1806): onScreenOff
,D/AutoSetting( 1502): service - handleMessage() stop self
,D/AutoSetting( 1502): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3931
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1502): service - handleMessage() quit looper
I/ActivityManager(  907): Killing 3931:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3931
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I,/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1167): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1167): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1167): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000113781507
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000113781532
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000113781555
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000113781544
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42500740 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42500740 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42500740 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 113781507, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 113781532, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 113781555, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 113781544, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ActivityManager(  907): Killing 3854:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3854
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3854
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4260bb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4260bb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1167): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1167): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1167): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1167): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1167): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1167): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1167): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1167): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (619) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000132055088
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000132055115
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000132055136
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
,I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000132055125
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000132055144
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 132055088, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 132055115, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 132055136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 132055125, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 132055144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/AutoSetting( 1400): service - handleMessage() stop self
,D/PMS     (  907): acquireWL(41cef768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4239b538: PendingIntentRecord{42478728 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141179, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4266ca90: PendingIntentRecord{424fe8d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141318, Int=0
,D/AutoSetting( 1400): service - onDestroy() END
,D/AutoSetting( 1400): service - handleMessage() quit looper,
D/Process (  907): killProcessQuiet, pid=3952
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3952:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3952
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(424ce320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10028)
,D/PMS     (  907): releaseWL(41cef768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/PMS     (  907): acquireWL(4258a080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =56a1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
D/PMS     (  907): releaseWL(4258a080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(424ce320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1167): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1167): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1167): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1167): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167),: send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1167): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1167): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1167): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1167): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (619) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000150294925
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000150294951
,I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000132055136
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56,
I/wpa_supplicant( 1167): tsf=0000000150294961
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000150294980
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 150294925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 150294951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 132055136, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 150294961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 150294980, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4266a800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4266a800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1167): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1167): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1167): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167),: [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1167): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1167): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1167): Add randomness: count=41 entropy=35
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (619) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000150294925
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000168619184,
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000168619197
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000150294961
,I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000168619206
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 150294925, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 168619184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 168619197, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 150294961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 168619206, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  907): acquireWL(426f4220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426f4220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1113): closing low battery warning: level=100
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42613650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{424d4af0: PendingIntentRecord{426d9870 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173633, Int=0
,D/PMS     (  907): releaseWL(42613650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1167): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1167): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
,I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
,D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1167): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1167): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (506) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000186854907
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000186854933
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000186854946
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000168619206
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 186854907, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 186854933, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 186854946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 168619206, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1,
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4262a0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end,
,D/UsbnetService(  907): BroadcastReceiver::onReceive+,
,D/PMS     (  907): releaseWL(4262a0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1167): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1167): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1167): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1167): Add randomness: count=53 entropy=47
D/wp,a_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000205094951
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000205094978
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000205094989
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 205094951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 205094978, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 205094989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter,
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1167): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1167): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1167): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1167): Add randomness: count=59 entropy=53
D/wp,a_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000223441758
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000223441784
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000223441795
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos,
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 223441758, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 223441784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 223441795, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4264dc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225362, Int=0,
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  907): releaseWL(4264dc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  907): acquireWL(426f72a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end,
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(426f72a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1167): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1167): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1167): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1167): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1167): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
,I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1167): 5: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
,I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1167): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1167): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1167): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1167): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1167): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
,D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1167): reply (776) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000241715115
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000241715141
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000241715152
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=5
I/wpa_supplicant( 1167): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-88
I/wpa_supplicant( 1167): tsf=0000000241715161
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=6
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000241715182
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=7
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000241715173
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS],
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 241715115, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 241715141, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 241715152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 241715161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 241715182, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 241715173, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  907): acquireWL(427480a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(427480a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1167): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1167): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1167): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1167): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl8021,1: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1167): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1167): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1167): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1167): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1167): reply (776) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
,I/wpa_supplicant( 1167): tsf=0000000259954848
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000259954875
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000259954886
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=5
I/wpa_supplicant( 1167): bssid=dc:4a:3e:0f:c2:f1,
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-88
I/wpa_supplicant( 1167): tsf=0000000241715161
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=6
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000259954905
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====,
I/wpa_supplicant( 1167): id=7
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000259954896
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 259954848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 259954875, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 259954886, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 241715161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 259954905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 259954896, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults,
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter,
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1167): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1167): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1167): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1167): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl8021,1: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1167): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1167): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1167): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1167): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (631) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000278292103
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000278292131
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000278292142
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=6
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000278292160
I/wpa_supplicant( 1167):, flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=7
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000278292151
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 278292103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 278292131, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 278292142, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 278292160, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 278292151, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42788828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=285361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42788828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4278aae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4278aae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1167): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1167): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1167,): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1167): Add randomness: count=97 entropy=91
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (631) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
,I/wpa_supplicant( 1167): tsf=0000000296514693
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000296514721
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000296514731
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
,I/wpa_supplicant( 1167): id=6
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000278292160
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=7
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000278292151
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 296514693, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 296514721, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 296514731, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 278292160, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 278292151, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427ac518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427ac518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1167): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1167): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1167): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1167): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000314754687
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
,I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000314754713
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000296514731
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 314754687, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 314754713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 296514731, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1167): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1167): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=107 entropy=101
D/wpa_supplicant,( 1167): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1167): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000333111326
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000333111353
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000333111364
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 333111326, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 333111353, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 333111364, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(427d6608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=345361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427d6608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1167): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1167): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1167): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1167): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,7): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1167): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1167): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1167): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1167): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (631) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000351394854
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000351394881
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-76
I/wpa_supplicant( 1167): tsf=0000000351394904
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=8
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000351394891
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=9
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000351394913
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 351394854, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 351394881, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 351394904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 351394891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 351394913, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427f3368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(427f3368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4303 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
D/PMS     (  907): acquireWL(427fb060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10047}
,V/AlarmManager(  907): sending alarm PendingIntent{423e3d48: PendingIntentRecord{4234c6e8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454717755586, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{426f5710: PendingIntentRecord{42568190 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1454717890485, Int=0
,D/PMS     (  907): releaseWL(427fb060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4303/10047)
,W/Uploader( 1226): No account for auth token provided
,D/Process (  907): killProcessQuiet, pid=2752
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2752:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7d46 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 42,
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
I/global  ( 1226): call createSocket() return a new socket.
D/libc    ( 1226): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-, SUCCESS,
,I/ActivityManager(  907): Recipient 2752
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1363): GoogleAccountDataService.getToken()
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1363): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1363): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1363): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1363): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1363): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1363): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1363): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1363): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 4054): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4054): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4054): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4054): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4054): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4054): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4054): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4054): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e61528 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 6 12 3 12
,D/libc    ( 4054): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4054): [NET] getaddrinfo-,err=8
D/libc    ( 4054): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4054): [NET] getaddrinfo-, 1
,D/libc    ( 4054): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  365): [NET] +++++ res_nsend xid =5ee5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4054): [NET] getaddrinfo_proxy-, success
I/global  ( 4054): call createSocket() return a new socket.
D/libc    ( 4054): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4054): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4054): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4054): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1167): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1167): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1167): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1167): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,7): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1167): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1167): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1167): Add randomness: count=128 entropy=122
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (631) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000369614798
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000369614824
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
,I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000369614845
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=8
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000369614835
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=9
,I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000369614854
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 369614798, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 369614824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 369614845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 369614835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 369614854, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428687e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428687e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1167): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1167): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1167): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1167): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,7): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1167): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1167): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1167): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1167): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (631) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000387834684
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000387834710
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000369614845
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=8
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000387834721
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=9
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000387834744
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ####
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 387834684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 387834710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 369614845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 387834721, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 387834744, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(4288a620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=405361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4288a620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1167): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1167): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1167): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a f,req=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1167): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1167): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1167): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (762) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000406135016
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000406135043
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000369614845
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=8
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000387834721
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
,I/wpa_supplicant( 1167): id=9
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000387834744
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=10
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000406135063
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 406135016, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 406135043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 369614845, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 387834721, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 387834744, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 406135063, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(428aaae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428aaae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1167): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1167): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1167): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a f,req=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1167): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1167): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1167): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (507) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000424354785
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_s,upplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000424354813
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000369614845
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=10
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000424354833
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 424354785, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 424354813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 369614845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 424354833, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428c3d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428c3d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1167): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1167): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1167): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1167): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1167): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1167): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (507) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000442624757
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000442624784
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000442624797
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=10
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000442624806
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 442624757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 442624784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 442624797, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 3: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 442624806, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available,
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing,
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1167): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1167): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0,
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
,I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1167): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1167): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (507) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000460951932
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000460951958
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000460951969
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=10
I/wpa_supplicant( 1167): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000442624806
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC243894600
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 460951932, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 460951958, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 460951969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 442624806, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(42659858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=465361, Int=0
,D/PMS     (  907): releaseWL(42659858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42657030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42657030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1167): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1167): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=173 entropy=167
D/wpa_supplica,nt( 1167): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1167): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000479204694
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====,
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000479204721
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000479204734
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 479204694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 479204721, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 479204734, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42514658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42514658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1167): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1167): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=179 entropy=173
D/wpa_supplica,nt( 1167): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1167): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000497212081
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000497212106
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000497212117
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 497212081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 497212106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 497212117, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1167): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1167): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=185 entropy=179
D/wpa_supplica,nt( 1167): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1167): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
,I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000515518980
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000515519007
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000515519018
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 515518980, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 515519007, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 515519018, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425a1778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=525362, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425a1778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42547328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42547328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1167): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1167): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1167): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1167): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1167): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 5: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x501
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan,0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1167): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1167): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1167): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1167): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1167): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (728) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000533794596
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000533794622
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000533794633
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=11
I/wpa_supplicant( 1167): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000533794653
I/wpa_supplicant( 1167): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=12
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000533794642
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=13
I/wpa_supplicant( 1167): bssid=44:e9:dd:10:c0:ad
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000533794662
I/wpa_supplicant( 1167): flags=[ESS]
I/wpa_supplicant( 1167): ssid=Darmowe_Orange_WiFi
I/wpa_supplicant( 1167): ####,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 533794596, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 533794622, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 533794633, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 533794653, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 533794642, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: Darmowe_Orange_WiFi, BSSID: 44:e9:dd:10:c0:ad, capabilities: [ESS], level: -93, frequency: 2462, timestamp: 533794662, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:              Darmowe_Orange_WiFi [44:e9:dd:10:c0:ad], Rssi:  0 [-93], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==,
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4236cb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4236cb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1167): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1167): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1167): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1167): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1167): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 5: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x501
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan,0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1167): Add randomness: count=207 entropy=201
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1167): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1167): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1167): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (728) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000552045067
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000552045093
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000552045104
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=11
I/wpa_supplicant( 1167): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000552045123
I/wpa_supplicant( 1167): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free,
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=12
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000552045114
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=13
I/wpa_supplicant( 1167): bssid=44:e9:dd:10:c0:ad
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000552045134
I/wpa_supplicant( 1167): flags=[ESS]
I/wpa_supplicant( 1167): ssid=Darmowe_Orange_WiFi
I/wpa_supplicant( 1167): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 552045067, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 552045093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 552045104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 552045123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 552045114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: Darmowe_Orange_WiFi, BSSID: 44:e9:dd:10:c0:ad, capabilities: [ESS], level: -93, frequency: 2462, timestamp: 552045134, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:              Darmowe_Orange_WiFi [44:e9:dd:10:c0:ad], Rssi:  0 [-93], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1167): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1167): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1167): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1167): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1167): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 5: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x501
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan,0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-93
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1167): [NULL] 44:e9:dd:10:c0:ad freq=2462 level=-93
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1167): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1167): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1167): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1167): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1167): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (728) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000570390515
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000570390541
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000570390552
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=11
I/wpa_supplicant( 1167): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000570390571
I/wpa_supplicant( 1167): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=12
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000570390562
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=13
I/wpa_supplicant( 1167): bssid=44:e9:dd:10:c0:ad
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000570390581
I/wpa_supplicant( 1167): flags=[ESS]
I/wpa_supplicant( 1167): ssid=Darmowe_Orange_WiFi
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 570390515, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 570390541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 570390552, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 570390571, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 570390562, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: Darmowe_Orange_WiFi, BSSID: 44:e9:dd:10:c0:ad, capabilities: [ESS], level: -93, frequency: 2462, timestamp: 570390581, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:              Darmowe_Orange_WiFi [44:e9:dd:10:c0:ad], Rssi:  0 [-93], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427857b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=585361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427857b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1167): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1167): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=227 entropy=221
D/wpa_supplica,nt( 1167): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1167): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (728) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000588664667
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000588664694
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
,I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000588664705
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=11
I/wpa_supplicant( 1167): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-91
I/wpa_supplicant( 1167): tsf=0000000570390571
I/wpa_supplicant( 1167): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=12
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000570390562,
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=13
I/wpa_supplicant( 1167): bssid=44:e9:dd:10:c0:ad
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-93
I/wpa_supplicant( 1167): tsf=0000000570390581
I/wpa_supplicant( 1167): flags=[ESS]
I/wpa_supplicant( 1167): ssid=Darmowe_Orange_WiFi
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 588664667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 588664694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 588664705, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 570390571, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -93, frequency: 2412, timestamp: 570390562, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: Darmowe_Orange_WiFi, BSSID: 44:e9:dd:10:c0:ad, capabilities: [ESS], level: -93, frequency: 2462, timestamp: 570390581, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:              Darmowe_Orange_WiFi [44:e9:dd:10:c0:ad], Rssi:  0 [-93], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-93], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425a2850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425a2850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1167): Add randomness: count=231 entropy=225
D/wpa_supplicant( 1167): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=233 entropy=227
D/wpa_supplica,nt( 1167): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1167): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000606923612
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000606923637
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412,
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000606923649
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 606923612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 606923637, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 606923649, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(42619150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(42619150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=236 entropy=230
D/wpa_supplicant( 1167): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1167): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=239 entropy=233
D/wpa_supplica,nt( 1167): Add randomness: count=240 entropy=234
D/wpa_supplicant( 1167): Add randomness: count=241 entropy=235
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000625124936
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000625124962
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000625124974
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 625124936, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 625124962, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 625124974, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1167): Add randomness: count=243 entropy=237
D/wpa_supplicant( 1167): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=245 entropy=239
D/wpa_supplica,nt( 1167): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1167): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000643452404
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000643452430
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000643452441
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 643452404, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 643452430, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 643452441, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427762b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=645361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427762b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=248 entropy=242
D/wpa_supplicant( 1167): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1167): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplica,nt( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1167): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1167): Add randomness: count=253 entropy=247
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000661711865
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000661711892
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000661711904
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 661711865, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 661711892, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 661711904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=4008
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4008:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4008
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42738eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(42738eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1167): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1167): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=257 entropy=251
D/wpa_supplica,nt( 1167): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1167): Add randomness: count=259 entropy=253
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000679915049
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000679915075
,I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000679915086
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 679915049, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 679915075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 679915086, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1167): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1167): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=263 entropy=257
D/wpa_supplica,nt( 1167): Add randomness: count=264 entropy=258
D/wpa_supplicant( 1167): Add randomness: count=265 entropy=259
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000698209281
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000698209308
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700,
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000698209319
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 698209281, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  907): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 698209308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 698209319, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426206d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=705362, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426206d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(426319c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426319c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=266 entropy=260
D/wpa_supplicant( 1167): Add randomness: count=267 entropy=261
D/wpa_supplicant( 1167): Add randomness: count=268 entropy=262
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=269 entropy=263
D/wpa_supplica,nt( 1167): Add randomness: count=270 entropy=264
D/wpa_supplicant( 1167): Add randomness: count=271 entropy=265
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000698209281
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000716424549
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-82
I/wpa_supplicant( 1167): tsf=0000000716424560
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 698209281, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 716424549, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 716424560, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427f72e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(427f72e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=272 entropy=266
D/wpa_supplicant( 1167): Add randomness: count=273 entropy=267
D/wpa_supplicant( 1167): Add randomness: count=274 entropy=268
D/wpa_supplicant( 1167): Add randomness: count=275 entropy=269
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=276 entropy=270
D/wpa_supplicant( 1167): Add randomness: count=277 entropy=271
D/wpa_supplicant( 1167): Add randomness: count=278 entropy=272
D/wpa_supplicant( 1167): Add randomness: count=279 entropy=273
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000734751381
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000734751407
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-83
I/wpa_supplicant( 1167): tsf=0000000734751431
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=14
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000734751420
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 734751381, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 734751407, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 734751431, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 734751420, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=280 entropy=274
D/wpa_supplicant( 1167): Add randomness: count=281 entropy=275
D/wpa_supplicant( 1167): Add randomness: count=282 entropy=276
D/wpa_supplicant( 1167): Add randomness: count=283 entropy=277
D/wpa_supplicant( 1167): Add randomness: count=284 entropy=278
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl,80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=285 entropy=279
D/wpa_supplicant( 1167): Add randomness: count=286 entropy=280
D/wpa_supplicant( 1167): Add randomness: count=287 entropy=281
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): Add randomness: count=288 entropy=282
D/wpa_supplicant( 1167): Add randomness: count=289 entropy=283
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (604) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000753015308
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000753015335
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000753015360,
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=14
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000753015347
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=15
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000753015369
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 753015308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 753015335, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 753015360, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 753015347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -92, frequency: 2412, timestamp: 753015369, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-92], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427b1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=765362, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427b1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=290 entropy=284
D/wpa_supplicant( 1167): Add randomness: count=291 entropy=285
D/wpa_supplicant( 1167): Add randomness: count=292 entropy=286
D/wpa_supplicant( 1167): Add randomness: count=293 entropy=287
D/wpa_supplicant( 1167): Add randomness: count=294 entropy=288
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1167): nl,80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/wpa_supplicant( 1167): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=295 entropy=289
D/wpa_supplicant( 1167): Add randomness: count=296 entropy=290
D/wpa_supplicant( 1167): Add randomness: count=297 entropy=291
D/wpa_supplicant( 1167): Add randomness: count=298 entropy=292
D/wpa_supplicant( 1167): Add randomness: count=299 entropy=293
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (604) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000753015308
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000771014462
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000771014485
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=14
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000771014474
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=15
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000771014494
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 753015308, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 771014462, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 771014485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 771014474, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -92, frequency: 2412, timestamp: 771014494, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-92], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427aadc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427aadc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=300 entropy=294
D/wpa_supplicant( 1167): Add randomness: count=301 entropy=295
D/wpa_supplicant( 1167): Add randomness: count=302 entropy=296
D/wpa_supplicant( 1167): Add randomness: count=303 entropy=297
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1167): 3: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1167): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-92
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=304 entropy=298
D/wpa_supplicant( 1167): Add randomness: count=305 entropy=299
D/wpa_supplicant( 1167): Add randomness: count=306 entropy=300
D/wpa_supplicant( 1167): Add randomness: count=307 entropy=301
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (604) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000789254650
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000789254676,
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000789254689
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=14
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000771014474
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=15
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000789254699
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 789254650, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 789254676, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 789254689, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 771014474, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -92, frequency: 2412, timestamp: 789254699, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  92, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  82, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-92], Tx: 13, Freq:  4 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428bc810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428bc810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=308 entropy=302
D/wpa_supplicant( 1167): Add randomness: count=309 entropy=303
D/wpa_supplicant( 1167): Add randomness: count=310 entropy=304
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=311 entropy=305
D/wpa_supplica,nt( 1167): Add randomness: count=312 entropy=306
D/wpa_supplicant( 1167): Add randomness: count=313 entropy=307
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000807411849
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000807411876
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000789254689
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=15
I/wpa_supplicant( 1167): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-92
I/wpa_supplicant( 1167): tsf=0000000789254699
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=WDA83
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 807411849, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 807411876, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 789254689, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -92, frequency: 2412, timestamp: 789254699, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  69, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-92], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427ea058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=825361, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427ea058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=314 entropy=308
D/wpa_supplicant( 1167): Add randomness: count=315 entropy=309
D/wpa_supplicant( 1167): Add randomness: count=316 entropy=310
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplica,nt( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=317 entropy=311
D/wpa_supplicant( 1167): Add randomness: count=318 entropy=312
D/wpa_supplicant( 1167): Add randomness: count=319 entropy=313
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000825501987
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000825502016
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000825502027
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 825501987, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 825502016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 825502027, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428a1a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(428a1a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=320 entropy=314
D/wpa_supplicant( 1167): Add randomness: count=321 entropy=315
D/wpa_supplicant( 1167): Add randomness: count=322 entropy=316
D/wpa_supplicant( 1167): Add randomness: count=323 entropy=317
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=324 entropy=318
D/wpa_supplicant( 1167): Add randomness: count=325 entropy=319
D/wpa_supplicant( 1167): Add randomness: count=326 entropy=320
D/wpa_supplicant( 1167): Add randomness: count=327 entropy=321
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000825501987
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000843805086
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000843805108
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000843805097
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 825501987, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 843805086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 843805108, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 843805097, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42849f20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42849f20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=328 entropy=322
D/wpa_supplicant( 1167): Add randomness: count=329 entropy=323
D/wpa_supplicant( 1167): Add randomness: count=330 entropy=324
D/wpa_supplicant( 1167): Add randomness: count=331 entropy=325
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=332 entropy=326
D/wpa_supplicant( 1167): Add randomness: count=333 entropy=327
D/wpa_supplicant( 1167): Add randomness: count=334 entropy=328
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): Add randomness: count=335 entropy=329
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000862044690
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000862044717
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000862044742
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000862044728
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 862044690, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 862044717, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 862044742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 862044728, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=336 entropy=330
D/wpa_supplicant( 1167): Add randomness: count=337 entropy=331
D/wpa_supplicant( 1167): Add randomness: count=338 entropy=332
D/wpa_supplicant( 1167): Add randomness: count=339 entropy=333
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=340 entropy=334
D/wpa_supplicant( 1167): Add randomness: count=341 entropy=335
D/wpa_supplicant( 1167): Add randomness: count=342 entropy=336
D/wpa_supplicant( 1167): Add randomness: count=343 entropy=337
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
,W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000880381889
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000880381916
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
,I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000880381937
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000880381926
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 880381889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 880381916, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 880381937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 880381926, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42700e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=885361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42700e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(427030a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(427030a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=344 entropy=338
D/wpa_supplicant( 1167): Add randomness: count=345 entropy=339
D/wpa_supplicant( 1167): Add randomness: count=346 entropy=340
D/wpa_supplicant( 1167): Add randomness: count=347 entropy=341
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c,2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=348 entropy=342
D/wpa_supplicant( 1167): Add randomness: count=349 entropy=343
D/wpa_supplicant( 1167): Add randomness: count=350 entropy=344
D/wpa_supplicant( 1167): Add randomness: count=351 entropy=345
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000898624713
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000898624752
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000000898624762
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000898624742
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 898624713, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 898624752, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 898624762, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 898624742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428ea760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428ea760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=352 entropy=346
D/wpa_supplicant( 1167): Add randomness: count=353 entropy=347
D/wpa_supplicant( 1167): Add randomness: count=354 entropy=348
D/wpa_supplicant( 1167): Add randomness: count=355 entropy=349
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=356 entropy=350
D/wpa_supplicant( 1167): Add randomness: count=357 entropy=351
D/wpa_supplicant( 1167): Add randomness: count=358 entropy=352
D/wpa_supplicant( 1167): Add randomness: count=359 entropy=353
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000916959012
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000916959049
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000916959064
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000916959038
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 916959012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 916959049, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 916959064, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 916959038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=360 entropy=354
D/wpa_supplicant( 1167): Add randomness: count=361 entropy=355
D/wpa_supplicant( 1167): Add randomness: count=362 entropy=356
D/wpa_supplicant( 1167): Add randomness: count=363 entropy=357
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): S,orted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=364 entropy=358
D/wpa_supplicant( 1167): Add randomness: count=365 entropy=359
D/wpa_supplicant( 1167): Add randomness: count=366 entropy=360
D/wpa_supplicant( 1167): Add randomness: count=367 entropy=361
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000935212328
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000935212364
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000935212374
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000935212353
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 a,ndroid.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 935212328, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 935212364, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 935212374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 935212353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42673bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=945361, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42673bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42659858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42659858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=368 entropy=362
D/wpa_supplicant( 1167): Add randomness: count=369 entropy=363
D/wpa_supplicant( 1167): Add randomness: count=370 entropy=364
D/wpa_supplicant( 1167): Add randomness: count=371 entropy=365
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=372 entropy=366
D/wpa_supplicant( 1167): Add randomness: count=373 entropy=367
D/wpa_supplicant( 1167): Add randomness: count=374 entropy=368
D/wpa_supplicant( 1167): Add randomness: count=375 entropy=369
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000953484986
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000953485015
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-78
I/wpa_supplicant( 1167): tsf=0000000953485039
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000953485026
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 953484986, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 953485015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 953485039, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 953485026, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(421c84b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end,
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(421c84b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=376 entropy=370
D/wpa_supplicant( 1167): Add randomness: count=377 entropy=371
D/wpa_supplicant( 1167): Add randomness: count=378 entropy=372
D/wpa_supplicant( 1167): Add randomness: count=379 entropy=373
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=380 entropy=374
D/wpa_supplicant( 1167): Add randomness: count=381 entropy=375
D/wpa_supplicant( 1167): Add randomness: count=382 entropy=376
D/wpa_supplicant( 1167): Add randomness: count=383 entropy=377
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000971792667
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000971792685
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000971792700
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000971792693
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 971792667, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 971792685, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 971792700, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 971792693, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=384 entropy=378
D/wpa_supplicant( 1167): Add randomness: count=385 entropy=379
D/wpa_supplicant( 1167): Add randomness: count=386 entropy=380
D/wpa_supplicant( 1167): Add randomness: count=387 entropy=381
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): S,orted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=388 entropy=382
D/wpa_supplicant( 1167): Add randomness: count=389 entropy=383
D/wpa_supplicant( 1167): Add randomness: count=390 entropy=384
D/wpa_supplicant( 1167): Add randomness: count=391 entropy=385
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000000990001844
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000000990001871
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000000990001894
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000990001884
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 990001844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 990001871, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 990001894, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 990001884, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(422cdf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1005362, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(422cdf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=392 entropy=386
D/wpa_supplicant( 1167): Add randomness: count=393 entropy=387
D/wpa_supplicant( 1167): Add randomness: count=394 entropy=388
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=395 entropy=389
D/wpa_supplica,nt( 1167): Add randomness: count=396 entropy=390
D/wpa_supplicant( 1167): Add randomness: count=397 entropy=391
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001008061901
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001008061929
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001008061942
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=16
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000000990001884
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1008061901, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1008061929, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1008061942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 990001884, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42673d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41d7f960: PendingIntentRecord{423de1a0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783981, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4234f958: PendingIntentRecord{42500800 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=926290, Int=0
D/PMS     (  907): acquireWL(425cc528): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1363 10028 null
,V/AlarmManager(  907): sending alarm PendingIntent{4255b7b8: PendingIntentRecord{425226b0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454718403338, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42394a58: PendingIntentRecord{423316d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454718475941, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{422ea1e8: PendingIntentRecord{42722568 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454718545796, Int=0
,D/PMS     (  907): releaseWL(425cc528): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(4272c1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
,D/PMS     (  907): releaseWL(4272c1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  907): acquireWL(425a6cf0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1226 10028 null
,D/PMS     (  907): acquireWL(428b3858): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(425a6cf0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1226): Aggregate from 1454717587913 (log), 1454716603250 (data)
D/PMS     (  907): acquireWL(42508b78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10028 null
W/ContextImpl( 4266): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4266): call getInstance()
,D/SmartSyncUtils( 4266): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4266): MY_DEBUG = false
D/PMS     (  907): releaseWL(42673d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4266): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4266): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
D/PMS     (  907): acquireWL(424d18e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4266 1000 null
D/GCM     ( 1363): Message class mow
D/SmartSyncScreenOnOffTimeReceiver( 4266): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4266): SettingOnTime = 1454796000000, randomSettingOnTime = 1454794187000
,D/SmartSyncScreenOnOffTimeReceiver( 4266): SettingOffTime = 1454785200000, randomSettingOffTime = 1454791089000
,D/SmartSyncScreenOnOffTimeReceiver( 4266): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4266): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4266): bNightModeTurnOffOnce = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1363/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10028)
,D/PMS     (  907): releaseWL(42508b78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): acquireWL(4255b858): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
,D/PMS     (  907): releaseWL(424d18e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): releaseWL(428b3858): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
D/PMS     (  907): releaseWL(4255b858): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  907): Grow heap (frag case) to 17.795MB for 148580-byte allocation
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(422def58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(422def58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=398 entropy=392
D/wpa_supplicant( 1167): Add randomness: count=399 entropy=393
D/wpa_supplicant( 1167): Add randomness: count=400 entropy=394
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=401 entropy=395
D/wpa_supplica,nt( 1167): Add randomness: count=402 entropy=396
D/wpa_supplicant( 1167): Add randomness: count=403 entropy=397
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001026304754,
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001026304781
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001026304792
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1026304754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1026304781, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1026304792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425c5460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425c5460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=404 entropy=398
D/wpa_supplicant( 1167): Add randomness: count=405 entropy=399
D/wpa_supplicant( 1167): Add randomness: count=406 entropy=400
D/wpa_supplicant( 1167): Add randomness: count=407 entropy=401
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=408 entropy=402
D/wpa_supplicant( 1167): Add randomness: count=409 entropy=403
D/wpa_supplicant( 1167): Add randomness: count=410 entropy=404
D/wpa_supplicant( 1167): Add randomness: count=411 entropy=405
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001044564868
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001044564895
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001044564916
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=17
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000001044564905
I/wpa_supplicant( 1167): flags,=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1044564868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1044564895, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1044564916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1044564905, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=412 entropy=406
D/wpa_supplicant( 1167): Add randomness: count=413 entropy=407
D/wpa_supplicant( 1167): Add randomness: count=414 entropy=408
D/wpa_supplicant( 1167): Add randomness: count=415 entropy=409
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=416 entropy=410
D/wpa_supplicant( 1167): Add randomness: count=417 entropy=411
D/wpa_supplicant( 1167): Add randomness: count=418 entropy=412
D/wpa_supplicant( 1167): Add randomness: count=419 entropy=413
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001062921501
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
,I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001062921526
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
,I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000001062921551
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=17
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000001062921539
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
,I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1062921501, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1062921526, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1062921551, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1062921539, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428f13d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1065362, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428f13d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42689af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42689af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=420 entropy=414
D/wpa_supplicant( 1167): Add randomness: count=421 entropy=415
D/wpa_supplicant( 1167): Add randomness: count=422 entropy=416
D/wpa_supplicant( 1167): Add randomness: count=423 entropy=417
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=424 entropy=418
D/wpa_supplicant( 1167): Add randomness: count=425 entropy=419
D/wpa_supplicant( 1167): Add randomness: count=426 entropy=420
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): Add randomness: count=427 entropy=421
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001081094764
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001081094792
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167),: tsf=0000001081094812
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=17
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000001081094802
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1081094764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1081094792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1081094812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1081094802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42890790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42890790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=428 entropy=422
D/wpa_supplicant( 1167): Add randomness: count=429 entropy=423
D/wpa_supplicant( 1167): Add randomness: count=430 entropy=424
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=431 entropy=425
D/wpa_supplica,nt( 1167): Add randomness: count=432 entropy=426
D/wpa_supplicant( 1167): Add randomness: count=433 entropy=427
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001099334788
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001099334814
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000001081094812
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=17
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-56
I/wpa_supplicant( 1167): tsf=0000001081094802
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1099334788, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1099334814, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1081094812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1081094802, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=434 entropy=428
D/wpa_supplicant( 1167): Add randomness: count=435 entropy=429
D/wpa_supplicant( 1167): Add randomness: count=436 entropy=430
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=437 entropy=431
D/wpa_supplica,nt( 1167): Add randomness: count=438 entropy=432
D/wpa_supplicant( 1167): Add randomness: count=439 entropy=433
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001117659028
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001117659056
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-74
I/wpa_supplicant( 1167): tsf=0000001081094812
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1117659028, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1117659056, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1081094812, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42752e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1125362, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42752e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427f80d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(427f80d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=440 entropy=434
D/wpa_supplicant( 1167): Add randomness: count=441 entropy=435
D/wpa_supplicant( 1167): Add randomness: count=442 entropy=436
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=443 entropy=437
D/wpa_supplica,nt( 1167): Add randomness: count=444 entropy=438
D/wpa_supplicant( 1167): Add randomness: count=445 entropy=439
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220,
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001135894704
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001135894730
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001135894741
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1135894704, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1135894730, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1135894741, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(426f61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426f61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=446 entropy=440
D/wpa_supplicant( 1167): Add randomness: count=447 entropy=441
D/wpa_supplicant( 1167): Add randomness: count=448 entropy=442
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=449 entropy=443
D/wpa_supplica,nt( 1167): Add randomness: count=450 entropy=444
D/wpa_supplicant( 1167): Add randomness: count=451 entropy=445
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001154208804
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001154208831
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001154208844
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1154208804, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1154208831, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1154208844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=452 entropy=446
D/wpa_supplicant( 1167): Add randomness: count=453 entropy=447
D/wpa_supplicant( 1167): Add randomness: count=454 entropy=448
D/wpa_supplicant( 1167): Add randomness: count=455 entropy=449
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): S,orted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=456 entropy=450
D/wpa_supplicant( 1167): Add randomness: count=457 entropy=451
D/wpa_supplicant( 1167): Add randomness: count=458 entropy=452
D/wpa_supplicant( 1167): Add randomness: count=459 entropy=453
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001172522251
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001172522289
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001172522300
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=18
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001172522277
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1172522251, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1172522289, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1172522300, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1172522277, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428049b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1185362, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428049b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=460 entropy=454
D/wpa_supplicant( 1167): Add randomness: count=461 entropy=455
D/wpa_supplicant( 1167): Add randomness: count=462 entropy=456
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=463 entropy=457
D/wpa_supplicant,( 1167): Add randomness: count=464 entropy=458
D/wpa_supplicant( 1167): Add randomness: count=465 entropy=459
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001190764843
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
,I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001190764881
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001172522300
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=18
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001190764870
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1190764843, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1190764881, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1172522300, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1190764870, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4286aa20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4286aa20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=466 entropy=460
D/wpa_supplicant( 1167): Add randomness: count=467 entropy=461
D/wpa_supplicant( 1167): Add randomness: count=468 entropy=462
D/wpa_supplicant( 1167): Add randomness: count=469 entropy=463
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1167): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=470 entropy=464
D/wpa_supplicant( 1167): Add randomness: count=471 entropy=465
D/wpa_supplicant( 1167): Add randomness: count=472 entropy=466
D/wpa_supplicant( 1167): Add randomness: count=473 entropy=467
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001208961943
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001208961980
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001208961989
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=18
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001208961969
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1208961943, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1208961980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1208961989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1208961969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42871ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42871ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=474 entropy=468
D/wpa_supplicant( 1167): Add randomness: count=475 entropy=469
D/wpa_supplicant( 1167): Add randomness: count=476 entropy=470
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplica,nt( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=477 entropy=471
D/wpa_supplicant( 1167): Add randomness: count=478 entropy=472
D/wpa_supplicant( 1167): Add randomness: count=479 entropy=473
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (490) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001226982090
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001226982116
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001226982127
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=18
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001208961969
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1226982090, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1226982116, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1226982127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1208961969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=480 entropy=474
D/wpa_supplicant( 1167): Add randomness: count=481 entropy=475
D/wpa_supplicant( 1167): Add randomness: count=482 entropy=476
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=483 entropy=477
D/wpa_supplica,nt( 1167): Add randomness: count=484 entropy=478
D/wpa_supplicant( 1167): Add randomness: count=485 entropy=479
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001245342009
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001245342036
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001245342047
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1245342009, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1245342036, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1245342047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/PMS     (  907): acquireWL(427c5898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b130a8: PendingIntentRecord{41b03400 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1245362, Int=0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(427c5898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4270bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4270bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=486 entropy=480
D/wpa_supplicant( 1167): Add randomness: count=487 entropy=481
D/wpa_supplicant( 1167): Add randomness: count=488 entropy=482
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=489 entropy=483
D/wpa_supplica,nt( 1167): Add randomness: count=490 entropy=484
D/wpa_supplicant( 1167): Add randomness: count=491 entropy=485
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001263584601
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001263584627
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001263584638
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1263584601, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1263584627, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1263584638, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4258fba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4258fba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
,D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=492 entropy=486
D/wpa_supplicant( 1167): Add randomness: count=493 entropy=487
D/wpa_supplicant( 1167): Add randomness: count=494 entropy=488
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 9
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 0
I/wpa_supplicant( 1167): wpa_s->is_screen_on 0
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1167): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1167): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1167): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=495 entropy=489
D/wpa_supplica,nt( 1167): Add randomness: count=496 entropy=490
D/wpa_supplicant( 1167): Add randomness: count=497 entropy=491
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): clear disabled list - type=1
I/wpa_supplicant( 1167): No suitable network found
W/wpa_supplicant( 1167): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1167): State: INACTIVE -> INACTIVE
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1167): reply (376) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-45
I/wpa_supplicant( 1167): tsf=0000001281864780
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-55
I/wpa_supplicant( 1167): tsf=0000001281864807
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
,I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-75
I/wpa_supplicant( 1167): tsf=0000001281864818
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1281864780, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1281864807, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1281864818, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4352): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4352): ====startRecUseTime====
D/htc.customization.log.level( 4352):  is 
W/CustomizationLogLevel( 4352): Level value is invalid, use default level 2
D/CustomizationManager( 4352):  Read ACC file spent 0.130 (s)
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4352): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4352): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4352): Parsing tag category name = system
I/CustomizationCIDLoader( 4352): Parsing tag category name = application
I/CustomizationCIDLoader( 4352): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4352): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4352): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4352): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4352): Parsing tag category name = Settings
D/CustomizationManager( 4352):  Read CID file spent 0.202 (s)
D/CustomizationManager( 4352):  All configurations done spent 0.203 (s)
W/HtcNativeFlag( 4352): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4352): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4352): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4352): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4352, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{42200550 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/acms    ( 1876): Unregistering com.test.thalitest
D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
E/acms    ( 1876): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1419): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(427a47f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1419 10028 null
D/PMS     (  907): releaseWL(427a47f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/PackageManager(  907): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  907): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1285): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4367 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1338): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/FileUtils(  907): Failed to chmod(/data/system/users/0/package-restrictions.xml): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4367): install
I/ActivityManager(  907): Delaying start of: ServiceRecord{425d4990 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4367): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4367): loading existing secondary dex files
I/PeopleContactsSync( 1226): CP2 sync disabled
I/MultiDex( 4367): load found 1 secondary dex files
I/MultiDex( 4367): install done
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  907): acquireWL(4242c400): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1226): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1226): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1226): Writing status failed
I/ProviderInstaller( 4367): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(4242c400): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4389 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4389): install
I/MultiDex( 4389): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4389): loading existing secondary dex files
I/MultiDex( 4389): load found 1 secondary dex files
I/MultiDex( 4389): install done
E/SQLiteDatabase( 1226): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1226): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1226): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1226): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1226): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1226): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1226): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1226): Runtime exception while performing operation
E/ClearPendingStateOp( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1226): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1226): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1226): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1226): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1226): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1226): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1226): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1226): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1226): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1226): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1226): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1226): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1226): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4389): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
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
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SharedPreferencesImpl( 1209): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1400): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1400): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1400): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9b6838
W/[PluginManager]RegisterService( 1400): provider may killed!
W/[PluginManager]RegisterService( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1400): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1400): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4367): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4367): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4367): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4367): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4367): threadid=12: thread exiting with uncaught exception (group=0x41672e30)
E/AndroidRuntime( 4367): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4367): Process: com.google.android.gms.drive, PID: 4367
E/AndroidRuntime( 4367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4367): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4367): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4367): 	at ctn.run(SourceFile:985)
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
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
D/Process ( 4367): killProcess, pid=4367
D/Process ( 4367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2897): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2897): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63d0b5d8
W/dalvikvm( 2897): threadid=14: thread exiting with uncaught exception (group=0x41672e30)
E/AndroidRuntime( 2897): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2897): Process: com.google.android.googlequicksearchbox:search, PID: 2897
E/AndroidRuntime( 2897): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2897): 	at cid.d(PG:186)
E/AndroidRuntime( 2897): 	at clo.g(PG:594)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2897): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2897): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2897): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2897): 	at clr.tL(PG:827)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2897): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2897): killProcess, pid=2897
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
D/Process ( 2897): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Recipient 4367
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4367) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2897
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2897) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2897): Died!
E/SQLiteDatabase( 1226): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1226): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1226): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1226): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1226): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1226): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1226): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1226): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1226): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1226): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1226): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1226): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1226): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1226): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1226): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1226): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1226): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1226): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1226): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1226): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1226): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1226): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1226): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1226): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1226): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1226): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1226): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1226): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1226): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1226): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1226): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 1226): threadid=10: thread exiting with uncaught exception (group=0x41672e30)
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4412 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 1226): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1226): Process: com.google.android.gms, PID: 1226
E/AndroidRuntime( 1226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1226): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1226): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1226): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1226): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1226): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1226): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1226): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1226): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
W/ActivityManager(  907): Process com.google.android.gms has crashed too many times: killing!
D/Process (  907): killProcessQuiet, pid=1226
I/ActivityManager(  907): Killing 1226:com.google.android.gms/u0a28 (adj 6): crash
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
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
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b35dd0 +
I/Prism.WidgetManager( 1273): onLoadItems() +
W/PackageManager(  907): Unable to load service info ResolveInfo{4257b3c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4

```
