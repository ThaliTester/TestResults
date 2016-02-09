#### Test 58135655e9e7eb8_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4269): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4269): ====startRecUseTime====
D/htc.customization.log.level( 4269):  is 
W/CustomizationLogLevel( 4269): Level value is invalid, use default level 2
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4269):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4269): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4269): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4269): Parsing tag category name = system
I/CustomizationCIDLoader( 4269): Parsing tag category name = application
I/CustomizationCIDLoader( 4269): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4269): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4269): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4269): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4269): Parsing tag category name = Settings
D/CustomizationManager( 4269):  Read CID file spent 0.104 (s)
D/CustomizationManager( 4269):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4269): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4269): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4269): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4269): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4269
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(423274a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423274a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,V/AlarmManager(  904): sending alarm PendingIntent{4259fc00: PendingIntentRecord{423b5378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=72578, Int=0
,I/CalendarProvider2( 1464): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1464): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42176f08): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3876 10154 null
,I/ActivityManager(  904): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3876): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3876): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3876, uid=10154, userID:0
,I/MusicLeanback( 3876): Conditions not met for autocaching.
,I/MusicLeanback( 3876): Stop autocaching.
D/PMS     (  904): releaseWL(42176f08): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4288 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4288): Loading default preferences
,W/Resources( 4288): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 4288): Overriding preferences with custom values
,D/SyncApplication( 4288): Updating preferences succeeded
,E/SyncApplication( 4288): Application created.
,D/VolumeInfo( 4288): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4288): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4288): Found 0 mount point(s)
,V/VolumeInfo( 4288): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4288): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4288): getNewCalendarAuthority()...
,D/VolumeInfo( 4288): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4288): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4288): enableAppOperation()+
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4288, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4288, uid=10008, userID:0
,W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4288): enableAppOperation()-
D/HTCUtilities( 4288): isNeorSinged() + 
,D/HTCUtilities( 4288): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4288): isNeorSinged() return false
,D/CDMountReceiver( 4288): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4288): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4288): enable CD Auto-mount: true
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4288): enable auto-mount
,D/HTCUtilities( 4288): enable auto-mount
,I/ActivityManager(  904): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  904): Resuming delayed broadcast
,D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41afd7c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 13 3 11
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b50bc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3857): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  904): killProcessQuiet, pid=3734
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3734:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3734
,I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4312 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=72 rxSum=54} preTxRxSum={txSum=55 rxSum=41}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=20140 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20141 delay=15s
D/PMS     (  904): releaseWL(425921b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4312): onCreate
D/ProviderChangeReceiver( 4312): ---------------------------------------------------
,D/ProviderChangeReceiver( 4312): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4312): start to updateAlertNotification!
,I/ActivityManager(  904): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4327 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  904): killProcessQuiet, pid=3895
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 3895:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3895
,D/AlertService( 4312): No fired or scheduled alerts
,D/HtcAlertUtils( 4312): -- cancelReminderNotification --
,D/HtcAlertUtils( 4312): broadcastExistReminder!
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4327): [4327/4327] onCreate()
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3929
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  904): Killing 3929:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3929
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 9 times.
,I/SensorManager(  904): mEventCount = 750
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{426f18e0 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:107, mTXpacketCount:89, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  904): releaseWL(423a0f90): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 10 times.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(425b5010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{42533f58: PendingIntentRecord{4258cd28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455021470394, Int=0
,D/PMS     (  904): releaseWL(425b5010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4163): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  904): mEventCount = 900
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 11 times.
,D/AutoSetting( 1397): service - has update message, not stop
,D/AutoSetting( 1397): service - mHandler: update timezone
,D/AutoSetting( 1464): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1464): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1464): service - onCreate()
,D/AutoSetting( 1464): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1464): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1464): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1464): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1464): service - mHandler: update timezone
,D/AutoSetting( 1464): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1464): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1464): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1464): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41bfe658 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 8 2 11
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=73 rxSum=55} preTxRxSum={txSum=72 rxSum=54}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=20141 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20142 delay=15s
D/PMS     (  904): acquireWL(42696830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{424b7f20: PendingIntentRecord{423b5378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88163, Int=0
D/PMS     (  904): releaseWL(42696830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1170): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 12 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  904): acquireWL(426abaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=91558, Int=0
,D/PMS     (  904): releaseWL(426abaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1115): now=1455021480057 next=59943
,I/SensorManager(  904): mEventCount = 1050
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:109, mTXpacketCount:107, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1464): Don't start project servcice
,D/HtcModeClient( 1464): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1464): connectState: CONNECTION_READY = false
,D/SilentMusic( 1464): call stop
,D/HtcModeClient( 1464): close connection
W/HtcModeClient( 1464): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1464): read the terminate packet, so break
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  904): acquireWL(426e95c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41d52418: PendingIntentRecord{4246c868 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=97643, Int=0
,D/PMS     (  904): acquireWL(4271c2d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): releaseWL(426e95c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4261e168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4271c2d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(4261e168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42679338 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  904): mEventCount = 1200
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  904): acquireWL(426ff2a0): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  904): releaseWL(426ff2a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(426c0c68): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  904): releaseWL(426c0c68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4239d758): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
,D/PMS     (  904): releaseWL(4239d758): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=74 rxSum=56} preTxRxSum={txSum=73 rxSum=55}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=20142 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20143 delay=15s
D/PMS     (  904): acquireWL(426efc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{425279c8: PendingIntentRecord{423b5378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103169, Int=0
D/PMS     (  904): releaseWL(426efc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4355 uid=10077 gids={50077}
D/PMS     (  904): acquireWL(426f60d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
V/AlarmManager(  904): sending alarm PendingIntent{422af250: PendingIntentRecord{420c27e0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455021493206, Int=60000
D/PMS     (  904): releaseWL(426f60d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4355): SMSBackupAgentService started
,D/SMSBackup( 4355): Checking restore status
,D/SMSBackup( 4355): Restore complete
,D/SMSBackup( 4355): cancelCheckAlarm
,D/SMSBackup( 4355): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3964
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 3964:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3964
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:110, mTXpacketCount:109, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  904): mEventCount = 1350
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f1610
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  904): mWirelessDisplayManager is null
V/LightsService(  904): setLight #2: color=#0
W/BatSI   (  904): Couldn't get kernel wake lock stats
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  904): setLight #0: color=#0
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f1610, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314fc8
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@41d9c010
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 413ms
,W/PnPMgr  (  355): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/NfcService( 1256): ScreenObserver: OFF
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  904): Disable input method client, pid=1270
D/NfcService( 1256): applyRouting - 0
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426a9a78)
D/PMN     (  904): wakingUp
,D/PMS     (  904): acquireWL(420cb170): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/NfcService( 1256): applyRouting -2
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): releaseWL(420cb170): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): acquireWL(425a5d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(425a5d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  904): onScreenOn
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2440): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2440): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
,D/AutoSetting( 1397): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting -2
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): acquireWL(426a2de0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/PMS     (  904): releaseWL(426a2de0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/ClockThread( 1115): stop update clock
,D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/HtcPowerSaver(  904): << updateStatus
,V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/        ( 4221): Cust_ConnectToPC   : IPT>true
,D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20144 delay=15s
,W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4221): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1170): SET_SCREEN_ON:On
I/wpa_supplicant( 1170): htc_wext_set_keepalive +
I/wpa_supplicant( 1170): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1170): getPrivFuncNum +	
I/wpa_supplicant( 1170): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1170): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1170): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1170): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1170): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4221): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/SmartNS_PSService( 4221): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4221):  defaultType:0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1170): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  904): updateScreenOn: false
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4380 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  904): acquireWL(42618240): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOn: 1455021500429
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOn: 1455021500430
D/PMS     (  904): releaseWL(42618240): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314fc8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314fc8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@41d9c010
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(4260f488): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d19260
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20144 mDataStallAlarmIntent=PendingIntent{421552f8: PendingIntentRecord{423b5378 android broadcastIntent}}
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
D/PMS     (  904): releaseWL(4260f488): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1170): SET_SCREEN_ON:Off
I/wpa_supplicant( 1170): htc_wext_set_keepalive +
I/wpa_supplicant( 1170): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1170): getPrivFuncNum +	
I/wpa_supplicant( 1170): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1170): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1170): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1170): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1170): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(426e83a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  904): updateScreenOn: false
,D/SmartSyncUtils( 4380): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(4261cf18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4380 1000 null
,D/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1170): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(426e83a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1170): nl80211: survey data missing!
E/wpa_supplicant( 1170): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1170): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4380): getMobilePolicyEnabled, result = true
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(4261cf18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/Process (  904): killProcessQuiet, pid=4012
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4012:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 52
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): start background delete task...
,I/ActivityManager(  904): Recipient 4012
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4380): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4380): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4380): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d9c010
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d9c010, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d9c010, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d9c010
D/AutoSetting( 1397): service - mHandler: cancel location update
,D/AutoSetting( 1397): service -           changes count: 0
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4248c488 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4248c488 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOff
D/PMS     (  904): acquireWL(426bce00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
D/PMS     (  904): releaseWL(426bce00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1464): service - handleMessage() stop self
,D/AutoSetting( 1464): service - onDestroy() END
,D/AutoSetting( 1464): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4034
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4034:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4034
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3910
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3910:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3910
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(42695d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42695d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42612d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{424ba380: PendingIntentRecord{424a3588 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141661, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{4274e770: PendingIntentRecord{423dffb8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142166, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(4261fa68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1362/10028)
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
D/PMS     (  904): releaseWL(42612d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  904): acquireWL(424c8160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  904): releaseWL(424c8160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/AutoSetting( 1397): service - handleMessage() stop self
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =57c5 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1397): service - onDestroy() END
,D/AutoSetting( 1397): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=3561
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3561:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,I/ActivityManager(  904): Recipient 3561
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(4261fa68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(42751c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42751c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4261d940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4261d940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4255f760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{4219b2e8: PendingIntentRecord{4254fe08 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175098, Int=0
,D/PMS     (  904): releaseWL(4255f760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  904): acquireWL(426be668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41d52418: PendingIntentRecord{4246c868 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=175560, Int=0
,D/PMS     (  904): acquireWL(426bf618): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(426be668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(426e6210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(426bf618): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(426e6210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2245/10028)
,D/PMS     (  904): acquireWL(426a4160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(426a4160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42720620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42720620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(427228c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(427228c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1115): closing low battery warning: level=100
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42705fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42705fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(426fc0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=271558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426fc0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42652590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42652590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42653e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=331557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42653e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(42656110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42656110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,W/GLSActivity( 1362): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1362): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1362): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1362): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1362): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1362): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1362): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1362): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e595f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4163): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4163): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4163): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4163): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4163): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 10 4 12
,D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4163): [NET] getaddrinfo-,err=8
D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4163): [NET] getaddrinfo-, 1
,D/libc    ( 4163): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8068 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4163): [NET] getaddrinfo_proxy-, success
I/global  ( 4163): call createSocket() return a new socket.
D/libc    ( 4163): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4163): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4163): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(42791d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42791d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(42799180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=391557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42799180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4279b508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(4279b508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(427a24b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427a24b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427a98f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=451558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427a98f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(427ac178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(427ac178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(427b31e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(427b31e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(427ba618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=511558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427ba618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(427bc8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(427bc8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(427c3868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(427c3868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427caca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=571557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427caca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(427ccf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427ccf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=98
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1596): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HtcPowerSaver(  904): updateBatteryInfo
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderNotification, total:1
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/        ( 4221): Cust_ConnectToPC   : IPT>true
,D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4221): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4221): Index of the first 1 = -1
W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4221): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4221): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427d7808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427d7808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  904): acquireWL(427dec10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=631557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427dec10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  904): killProcessQuiet, pid=4092
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4092:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4092
,D/PMS     (  904): acquireWL(427e5178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(427e5178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427ec520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=691558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427ec520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(427eeda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427eeda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427f6198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=751558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427f6198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(427f8438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427f8438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(427f9eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(427f9eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42801280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=811558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42801280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42803540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42803540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(428049f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(428049f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4280b5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=871557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4280b5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4280d858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4280d858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4280f158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=931558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4280f158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(428113d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428113d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42818598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42818598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderNotification, total:0
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetPhoneState( 1596): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/        ( 4221): Cust_ConnectToPC   : IPT>true
,D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4221): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4221): Index of the first 1 = -1
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4221): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42822170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=991557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42822170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42825778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{41dc8678: PendingIntentRecord{4240b0e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785463, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{423c29f8: PendingIntentRecord{42505430 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928990, Int=0
,D/PMS     (  904): acquireWL(42831900): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1362 10028 null
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): releaseWL(42831900): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4438 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{4216ff68: PendingIntentRecord{42412db0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455021609980, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{425d3250: PendingIntentRecord{422e8f10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455022330362, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42462398: PendingIntentRecord{425e7ad8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455022400574, Int=0
,D/PMS     (  904): acquireWL(4283a378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  904): releaseWL(4283a378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4380): call getInstance()
,D/SmartSyncUtils( 4380): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4380): MY_DEBUG = false
D/PMS     (  904): acquireWL(4283c318): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4380 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4380): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4380): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/PMS     (  904): releaseWL(42825778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4380): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4380): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082574000
D/SmartSyncScreenOnOffTimeReceiver( 4380): SettingOffTime = 1455062400000, randomSettingOffTime = 1455064188000
D/SmartSyncScreenOnOffTimeReceiver( 4380): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4380): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4380): bNightModeTurnOffOnce = false
,D/PMS     (  904): releaseWL(4283c318): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4438/10047)
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/Process (  904): killProcessQuiet, pid=3979
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3979:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3979
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42654c90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null,
,D/GCM     ( 1362): Message class mow
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1362/10028)
,D/PMS     (  904): releaseWL(42654c90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): acquireWL(42802fa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  904): releaseWL(42802fa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  904): acquireWL(4280d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4280d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(427d5c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1051557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427d5c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(427fcf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427fcf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(427efe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1111558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427efe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42811db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42811db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42741668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1171557, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42741668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4279cf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4279cf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(427e47f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4201f4a8: PendingIntentRecord{41e82a90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1231558, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427e47f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4283d7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4283d7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4455): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4455): ====startRecUseTime====
D/htc.customization.log.level( 4455):  is 
W/CustomizationLogLevel( 4455): Level value is invalid, use default level 2
D/CustomizationManager( 4455):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4455): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4455): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4455): Parsing tag category name = system
I/CustomizationCIDLoader( 4455): Parsing tag category name = application
I/CustomizationCIDLoader( 4455): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4455): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4455): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4455): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4455): Parsing tag category name = Settings
D/CustomizationManager( 4455):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4455):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4455): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4455): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4455): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4455): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4455, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  904): Skipping PackageSetting{422b8a18 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  904): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  904): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/acms    ( 1876): Unregistering com.test.thalitest
E/acms    ( 1876): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): acquireWL(4283f5d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
W/GeofencerStateMachine( 1447): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): releaseWL(4283f5d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2245): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4469 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/Parcel  ( 1256): Reading a NULL string not supported here.
F/PackageManager(  904): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  904): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
F/PackageManager(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  904): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  904): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  904): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  904): 	... 9 more
E/ExternalAccountType( 1330): Unsupported attribute readOnly
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1455022671404.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/ActivityManager(  904): Delaying start of: ServiceRecord{42796ef0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4469): install
I/PeopleContactsSync( 2245): CP2 sync disabled
I/MultiDex( 4469): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2245, uid=10028, userID:0
I/MultiDex( 4469): loading existing secondary dex files
I/MultiDex( 4469): load found 1 secondary dex files
I/MultiDex( 4469): install done
D/PMS     (  904): acquireWL(424fb4c0): PARTIAL_WAKE_LOCK  Icing 0x1 2245 10028 null
I/Icing   ( 2245): doRemovePackageData com.test.thalitest
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.corpusid-1
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2245): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2245): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2245): Writing status failed
D/PMS     (  904): releaseWL(424fb4c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4490 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4469): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 2245): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2245): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2245): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2245): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2245): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2245): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2245): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2245): Runtime exception while performing operation
E/ClearPendingStateOp( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2245): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2245): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2245): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2245): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2245): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2245): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2245): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2245): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2245): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2245): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2245): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2245): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2245): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4490): install
I/MultiDex( 4490): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4490): loading existing secondary dex files
I/MultiDex( 4490): load found 1 secondary dex files
I/MultiDex( 4490): install done
E/DropBoxManagerService(  904): Can't write: system_app_wtf
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 4490): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
E/SharedPreferencesImpl( 1206): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1397): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1397): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1397): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9ec348
W/[PluginManager]RegisterService( 1397): provider may killed!
W/[PluginManager]RegisterService( 1397): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1397): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1397): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1397): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1397): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1397): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1397): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1397): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1397): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4469): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4469): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4469): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4469): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4469): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4469): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4469): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4469): threadid=12: thread exiting with uncaught exception (group=0x4169de30)
I/IcingCorporaProvider( 2885): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/AndroidRuntime( 4469): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4469): Process: com.google.android.gms.drive, PID: 4469
E/AndroidRuntime( 4469): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4469): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4469): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4469): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4469): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4469): 	at ctn.run(SourceFile:985)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 4469): killProcess, pid=4469
D/Process ( 4469): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  904): Recipient 4469
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4469) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  904): Resuming delayed broadcast
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4511 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2885): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2885): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x645d9528
W/dalvikvm( 2885): threadid=14: thread exiting with uncaught exception (group=0x4169de30)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2885): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2885): Process: com.google.android.googlequicksearchbox:search, PID: 2885
E/AndroidRuntime( 2885): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2885): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2885): 	at cid.d(PG:186)
E/AndroidRuntime( 2885): 	at clo.g(PG:594)
E/AndroidRuntime( 2885): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2885): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2885): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2885): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2885): 	at clr.tL(PG:827)
E/AndroidRuntime( 2885): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2885): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2885): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2885): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2885): killProcess, pid=2885
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2885): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  904): Recipient 2885
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2885): Died!
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2885) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
E/SQLiteDatabase( 2245): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2245): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2245): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2245): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2245): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2245): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2245): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2245): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2245): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2245): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2245): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2245): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2245): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2245): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2245): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2245): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2245): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2245): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2245): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2245): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2245): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2245): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2245): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2245): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2245): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2245): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2245): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2245): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2245): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2245): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2245): Opened games_3a3529a.db in read-only mode
W/SQLiteConnectionPool( 2245): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2245): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2245): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/dalvikvm( 2245): threadid=10: thread exiting with uncaught exception (group=0x4169de30)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2245): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2245): Process: com.google.android.gms, PID: 2245
E/AndroidRuntime( 2245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2245): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2245): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2245): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2245): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2245): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2245): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2245): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  904): killProcessQuiet, pid=2245
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  904): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  904): Killing 2245:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  904): Can't write: system_app_crash
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
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
E/SQLiteDatabase( 4511): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4511): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4511): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4511): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4511): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4511): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4511): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4511): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4511): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4511): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4511): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4511): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4511): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4511): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4511): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4511): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4511): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4511): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4511): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4511): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4511): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4511): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4511): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4511): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4511): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4511): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4511): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4511): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4511): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4511): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4511): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4511): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4511): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4511): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4511): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4511): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4511): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4511): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4511): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4511): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4511): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4511): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4511): Opened ClientFlag.db in read-only mode

```
