#### Test 58751238ee11130_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/AlarmManager(  906): sending alarm PendingIntent{425b5dc0: PendingIntentRecord{424d1540 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71750, Int=0
D/PMS     (  906): acquireWL(42413da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42413da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of /dev/log/main
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/cutils-trace( 4242): Error opening trace file: No such file or directory (2)
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4242): ====startRecUseTime====
D/htc.customization.log.level( 4242):  is 
W/CustomizationLogLevel( 4242): Level value is invalid, use default level 2
I/CalendarProvider2( 1510): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 1510): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
D/CustomizationManager( 4242):  Read ACC file spent 0.050 (s)
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
D/PMS     (  906): acquireWL(42697838): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3900 10154 null
I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
V/CustomizationCIDLoader( 4242): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4242): Parsing tag category name = system
I/CustomizationCIDLoader( 4242): Parsing tag category name = application
I/CustomizationCIDLoader( 4242): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4242): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4242): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4242): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4242): Parsing tag category name = Settings
W/ContextImpl( 3900): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/CustomizationManager( 4242):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4242):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4242): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4242): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4242): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4242): Fail to get flag for type 'language', use default value: -1
W/ContextImpl( 3900): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3900, uid=10154, userID:0
I/MusicLeanback( 3900): Conditions not met for autocaching.
I/MusicLeanback( 3900): Stop autocaching.
D/PMS     (  906): releaseWL(42697838): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4258 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4242
D/SyncApplication( 4258): Loading default preferences
W/Resources( 4258): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  906): New client listening to asynchronous messages
D/SyncApplication( 4258): Overriding preferences with custom values
D/SyncApplication( 4258): Updating preferences succeeded
E/SyncApplication( 4258): Application created.
D/VolumeInfo( 4258): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4258): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4258): Found 0 mount point(s)
V/VolumeInfo( 4258): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4258): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4258): getNewCalendarAuthority()...
D/VolumeInfo( 4258): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 4258): Can not create volume ID for unmounted volume null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4258, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4258): enableAppOperation()+
D/SyncApplication( 4258): enableAppOperation()-
D/HTCUtilities( 4258): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4258, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 4258): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4258): isNeorSinged() return false
D/CDMountReceiver( 4258): whether to enable CD Auto-mount: true
D/CDMountReceiver( 4258): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
D/CDMountReceiver( 4258): enable CD Auto-mount: true
D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/HTCUtilities( 4258): enable auto-mount
D/HTCUtilities( 4258): enable auto-mount
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41f73cc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 3 22 5 11
I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b60ea8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 1 15 3 16
,W/MediaManager( 3860): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  906): killProcessQuiet, pid=3745
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3745:com.htc.sense.news/u0a75 (adj 15): empty #17
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  906): Recipient 3745
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4282 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=41 rxSum=31} preTxRxSum={txSum=34 rxSum=24}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19985 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19986 delay=15s
D/PMS     (  906): releaseWL(423befc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4282): onCreate
D/ProviderChangeReceiver( 4282): ---------------------------------------------------
,D/ProviderChangeReceiver( 4282): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4282): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4297 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3921
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3921:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AlertService( 4282): No fired or scheduled alerts
,D/HtcAlertUtils( 4282): -- cancelReminderNotification --
,D/HtcAlertUtils( 4282): broadcastExistReminder!
I/ActivityManager(  906): Recipient 3921
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4297): [4297/4297] onCreate()
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3955
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3955:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3955
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{426cf6f0 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 9 times.
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(4251bbe0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/SensorManager(  906): mEventCount = 600
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:66, mTXpacketCount:66, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 10 times.
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): acquireWL(42581010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{423ccbd8: PendingIntentRecord{424658a0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455027680707, Int=0
,D/PMS     (  906): releaseWL(42581010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4135): [1] 5.onFinished: Installation state replication succeeded.
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 11 times.
,D/AutoSetting( 1401): service - mHandler: update timezone
,D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/AutoSetting( 1401): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3979
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3979:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3979
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41bf5550 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=42 rxSum=32} preTxRxSum={txSum=41 rxSum=31}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19986 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19987 delay=15s
D/PMS     (  906): acquireWL(4229c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42579d18: PendingIntentRecord{424d1540 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88136, Int=0
D/PMS     (  906): releaseWL(4229c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 12 times.
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:69, mTXpacketCount:66, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1510): Don't start project servcice
,D/HtcModeClient( 1510): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1510): connectState: CONNECTION_READY = false
,D/SilentMusic( 1510): call stop
,D/HtcModeClient( 1510): close connection
,W/HtcModeClient( 1510): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1510): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4260fde0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216,
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(42509e00): PARTIAL_WAKE_LOCK  Icing 0x1 2237 10028 null
,D/PMS     (  906): releaseWL(42509e00): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425fddd0): PARTIAL_WAKE_LOCK  Icing 0x1 2237 10028 null
,D/PMS     (  906): releaseWL(425fddd0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425800a8): PARTIAL_WAKE_LOCK  Icing 0x1 2237 10028 null
,D/PMS     (  906): releaseWL(425800a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425f64f8): PARTIAL_WAKE_LOCK  Icing 0x1 2237 10028 null
,D/PMS     (  906): releaseWL(425f64f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall,
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=33} preTxRxSum={txSum=42 rxSum=32}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19987 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19988 delay=15s
D/PMS     (  906): acquireWL(42685928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423a0078: PendingIntentRecord{424d1540 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103141, Int=0
D/PMS     (  906): releaseWL(42685928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4322 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(4234b7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{41ef7350: PendingIntentRecord{4212fdf0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455027704028, Int=60000
,D/PMS     (  906): releaseWL(4234b7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4322): SMSBackupAgentService started
,D/SMSBackup( 4322): Checking restore status
,D/SMSBackup( 4322): Restore complete
,D/SMSBackup( 4322): cancelCheckAlarm
,D/SMSBackup( 4322): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=4005
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4005:com.htc.updater/u0a84 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4005
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:70, mTXpacketCount:69, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4206f8b0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4206f8b0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c404a8
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@422bfd40
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 406ms
,D/PMS     (  906): nativeSetInteractive:false
,W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
,I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1257): applyRouting -2
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@424296d0)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/PMS     (  906): acquireWL(426db650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/InputMethodManagerService(  906): Disable input method client, pid=1272
I/BatteryService(  906): n_update end
D/PMS     (  906): acquireWL(426e31b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  906): releaseWL(426db650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): releaseWL(426e31b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): wakingUp
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WindowManager(  906): No lock screen! windowToken=null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMN     (  906): onScreenOn
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2449): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2449): [MTP][onReceive]-
,D/NfcService( 1257): applyRouting - 0
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1401): receiver - intent: android.intent.action.USER_PRESENT
D/NfcService( 1257): applyRouting -2
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): acquireWL(4266a558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  906): releaseWL(4266a558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,D/AutoSetting( 1401): service - onCreate()
,I/ClockThread( 1116): stop update clock
,D/AutoSetting( 1401): service - AddressCache: using context: com.htc.Weather
I/HtcPowerSaver(  906): << updateStatus
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19989 delay=15s
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/LocationManagerService(  906): request 42437018 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:On
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
D/TetherSettings( 4191): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4191): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4191): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4191): Cust_ConnectToPC   : spcsc>false
D/        ( 4191): Cust_ConnectToPC   : IPT>true
D/        ( 4191): Cust_ConnectToPC   : Singel_USB>false
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
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
,W/Settings( 4191): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4191): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4191): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
V/SRS_Proc(  365): ParamSet string: screen_state=on
,D/SmartNS_NSReceiver( 4191): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WIFI_ICON( 1116): WifiActivity: 0
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/PSReceiver( 4191): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4191): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4191): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4191): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4191):  defaultType:0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4346 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(426b7590): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1796): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): onScreenOn: 1455027711761
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1796): onScreenOn: 1455027711762
D/PMS     (  906): releaseWL(426b7590): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c404a8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c404a8, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@422bfd40
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(427bc940): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1272): [onPause]
,I/FeedProviderManager( 1272): onPause
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
,I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4227cc30
W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19989 mDataStallAlarmIntent=PendingIntent{424ab060: PendingIntentRecord{424d1540 android broadcastIntent}}
,D/PMS     (  906): acquireWL(41aa9e58): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:Off
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1134): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(427bc940): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  365): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(425c16f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4346 1000 null
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(41aa9e58): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  906): releaseWL(425c16f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 ,
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/SmartSyncUtils( 4346): getMobilePolicyEnabled, result = true
,I/PhoneStatusBar( 1116): removeHeadsNotification.gc: 52
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4346): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(426c3f10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  906): releaseWL(426c3f10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1796): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1796): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1796): onScreenOff
,D/AutoSetting( 1401): service - mHandler: cancel location update
,D/AutoSetting( 1401): service -           changes count: 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422bfd40
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422bfd40, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422bfd40, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422bfd40,
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422202f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422202f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
,E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
,E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): ,	at dalvik.system.NativeStart.main(Native Method)
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4044
,I/ActivityManager(  906): Killing 4044:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1510): service - handleMessage() quit looper
,I/ActivityManager(  906): Recipient 4044
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3936
,I/ActivityManager(  906): Killing 3936:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3936
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426565f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426565f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{41a9cde0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(4269e940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4269e940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(426a5cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42470aa0: PendingIntentRecord{42470a20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141464, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41eb2c38: PendingIntentRecord{4239c3a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142354, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(426a7dd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(426a5cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): acquireWL(42718e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(42718e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =e312 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - onDestroy() END
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3633
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3633:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  358): [NET]res_nsend:resplen=243
D/libc    (  358): [NET]res_queryN: exit 3, ancount=10
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.,
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,I/ActivityManager(  906): Recipient 3633
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(426a7dd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2237/10028)
,D/PMS     (  906): acquireWL(42743fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42743fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4274ad90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4231cf00: PendingIntentRecord{42539aa0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174873, Int=0
,D/PMS     (  906): releaseWL(4274ad90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(4274d388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4274d388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4274f628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4274f628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42756688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42756688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4275da30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4275da30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4275fcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4275fcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42766d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42766d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
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
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4276e0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4276e0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42770398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42770398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4378 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  906): acquireWL(42772e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10047}
,V/AlarmManager(  906): sending alarm PendingIntent{41e159b0: PendingIntentRecord{421735d0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455027820267, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{4257da08: PendingIntentRecord{422a09a8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1455027945066, Int=0
,D/PMS     (  906): releaseWL(42772e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4378/10047)
,W/Uploader( 2237): No account for auth token provided
,D/Process (  906): killProcessQuiet, pid=3761
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3761:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3761
,D/libc    ( 2237): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2237): [NET] getaddrinfo-,err=8
D/libc    ( 2237): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2237): [NET] getaddrinfo-, 1
,D/libc    ( 2237): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =8840 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE,
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 21
D/libc    (  358): [NET]res_nsend:resplen=87
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2237): [NET] getaddrinfo_proxy-, success
,I/global  ( 2237): call createSocket() return a new socket.
D/libc    ( 2237): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2237): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2237): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2237): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2237/10028)
,W/Uploader( 2237): No account for auth token provided
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2237/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2237/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2237/10028)
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42784630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42784630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4278b998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4278b998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41bfacf8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 10 3 12
,E/PlayEventLogger( 4135): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4135): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4135): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4135): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4135): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4135): [NET] getaddrinfo-,err=8
D/libc    ( 4135): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4135): [NET] getaddrinfo-, 1
D/libc    ( 4135): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =4840 +++++
,D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4135): [NET] getaddrinfo_proxy-, success
I/global  ( 4135): call createSocket() return a new socket.
,D/libc    ( 4135): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4135): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4135): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4135): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(427b5600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(427b5600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427e8c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(427e8c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(427f00f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427f00f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427f2398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427f2398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
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
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(427f94a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427f94a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42800838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=480401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42800838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42802ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42802ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42809b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42809b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4280b950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=540401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4280b950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4280dc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4280dc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4280f168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4280f168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428164c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=600401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428164c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42818760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42818760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  906): acquireWL(4281a060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=660401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4281a060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4089
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4089:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4089
,D/PMS     (  906): acquireWL(4281f2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4281f2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428262b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428262b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4282dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=720401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4282dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4282fea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4282fea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428317a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=780401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428317a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42833a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42833a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4283aa28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4283aa28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427ed5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=840402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427ed5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427c73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427c73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426b0588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(426b0588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42671740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=900401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42671740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4266d638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4266d638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425e5b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e5b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
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
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425aadc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425aadc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425a4cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425a4cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
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
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(4244aeb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41db2908: PendingIntentRecord{423e4318 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784635, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42595bd0: PendingIntentRecord{423c8880 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928385, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42332250: PendingIntentRecord{422f8f68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455028540646, Int=900000
,D/PMS     (  906): acquireWL(4239c850): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10028 null
,V/AlarmManager(  906): sending alarm PendingIntent{41e080c8: PendingIntentRecord{4267f130 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455028611926, Int=0
,D/PMS     (  906): releaseWL(4239c850): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(41f9bcc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(41f9bcc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PowerUsageService( 4346): call getInstance()
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4346): MY_DEBUG = false
D/PMS     (  906): releaseWL(4244aeb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4250f6b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4346 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4346): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4346): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4346): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4346): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081923000
D/SmartSyncScreenOnOffTimeReceiver( 4346): SettingOffTime = 1455062400000, randomSettingOffTime = 1455065244000
D/SmartSyncScreenOnOffTimeReceiver( 4346): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4346): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4346): bNightModeTurnOffOnce = false
D/PMS     (  906): releaseWL(4250f6b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4281cb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1116): closing low battery warning: level=98
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1586): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderNotification, total:1
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4281cb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4191): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4191): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4191): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4191): Cust_ConnectToPC   : spcsc>false
D/        ( 4191): Cust_ConnectToPC   : IPT>true
D/        ( 4191): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4191): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4191): Index of the first 1 = -1
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4191): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4191): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4191): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4191): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4191): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4191): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4191): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42739608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/GCM     ( 1365): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): acquireWL(426148d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(426148d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(42739608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42616bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42616bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42618e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42618e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426215b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/BatteryService(  906): n_update end
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(426215b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=98
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42634478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1080402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42634478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42636718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42636718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4265f998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1140402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4265f998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42661c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42661c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427237d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d43a10: PendingIntentRecord{42445aa0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1164404, Int=0
,D/PMS     (  906): acquireWL(42724768): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(427237d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42726720): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42724768): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42726720): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(4272d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1200401, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4272d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4272f908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4272f908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(427d9160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427d9160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427e0578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41aa1890: PendingIntentRecord{42299720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1260402, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427e0578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427e28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427e28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4429): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4429): ====startRecUseTime====
D/htc.customization.log.level( 4429):  is 
W/CustomizationLogLevel( 4429): Level value is invalid, use default level 2
D/CustomizationManager( 4429):  Read ACC file spent 0.089 (s)
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4429): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4429): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4429): Parsing tag category name = system
I/CustomizationCIDLoader( 4429): Parsing tag category name = application
I/CustomizationCIDLoader( 4429): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4429): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4429): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4429): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4429): Parsing tag category name = Settings
D/CustomizationManager( 4429):  Read CID file spent 0.130 (s)
D/CustomizationManager( 4429):  All configurations done spent 0.130 (s)
W/HtcNativeFlag( 4429): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4429): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4429): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4429): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4429, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{4225c1c0 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/acms    ( 1899): Unregistering com.test.thalitest
E/acms    ( 1899): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1431): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(42042ae8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42042ae8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1286): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PackageBroadcastService( 2237): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4443 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 4443): install
I/MultiDex( 4443): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/MultiDex( 4443): loading existing secondary dex files
I/MultiDex( 4443): load found 1 secondary dex files
I/ActivityManager(  906): Delaying start of: ServiceRecord{4278b5a0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 4443): install done
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2237): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2237, uid=10028, userID:0
I/Icing   ( 2237): doRemovePackageData com.test.thalitest
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.corpusid-1
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2237): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2237): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2237): Writing status failed
D/PMS     (  906): acquireWL(41e79ff8): PARTIAL_WAKE_LOCK  Icing 0x1 2237 10028 null
D/PMS     (  906): releaseWL(41e79ff8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4443): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4464 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4464): install
I/MultiDex( 4464): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/SQLiteDatabase( 2237): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2237): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2237): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2237): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2237): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2237): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2237): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2237): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2237): Runtime exception while performing operation
E/ClearPendingStateOp( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2237): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2237): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2237): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2237): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2237): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2237): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2237): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2237): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2237): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2237): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2237): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2237): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2237): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2237): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2237): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4464): loading existing secondary dex files
I/MultiDex( 4464): load found 1 secondary dex files
I/MultiDex( 4464): install done
E/DropBoxManagerService(  906): Can't write: system_app_wtf
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
I/ProviderInstaller( 4464): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1401): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/SQLiteLog( 1401): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1401): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c88f010
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
I/[PluginManager]RegisterService( 1401): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
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
W/dalvikvm( 4443): threadid=12: thread exiting with uncaught exception (group=0x41675e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
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
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4443): killProcess, pid=4443
D/Process ( 4443): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2906): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 2906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x614800d0
W/dalvikvm( 2906): threadid=14: thread exiting with uncaught exception (group=0x41675e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2906): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2906): Process: com.google.android.googlequicksearchbox:search, PID: 2906
E/AndroidRuntime( 2906): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2906): 	at cid.d(PG:186)
E/AndroidRuntime( 2906): 	at clo.g(PG:594)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2906): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2906): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2906): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2906): 	at clr.tL(PG:827)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2906): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2906): killProcess, pid=2906
D/Process ( 2906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
W/PackageManager(  906): Unable to load service info ResolveInfo{4255abe8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  906): Recipient 4443
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4443) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  906): Resuming delayed broadcast
W/BroadcastQueue(  906): Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.GelStubAppWatcher}
W/BroadcastQueue(  906): android.os.TransactionTooLargeException
W/BroadcastQueue(  906): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  906): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.backgroundServicesFinishedLocked(BroadcastQueue.java:442)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.backgroundServicesFinishedLocked(ActivityManagerService.java:15042)
W/BroadcastQueue(  906): 	at com.android.server.am.ActiveServices$ServiceMap.rescheduleDelayedStarts(ActiveServices.java:237)
W/BroadcastQueue(  906): 	at com.android.server.am.ActiveServices$ServiceMap.ensureNotStartingBackground(ActiveServices.java:191)
W/BroadcastQueue(  906): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1711)
W/BroadcastQueue(  906): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2185)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:13536)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3943)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
W/BroadcastQueue(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/BroadcastQueue(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
I/ActivityManager(  906): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/.GelStubAppWatcher: pid=4486 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
E/SQLiteDatabase( 2237): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2237): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2237): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2237): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2237): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2237): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2237): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2237): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2237): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2237): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2237): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2237): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2237): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2237): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2237): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2237): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2237): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2237): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2237): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2237): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2237): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2237): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2237): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2237): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2237): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2237): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2237): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2237): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2237): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2237): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2237): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2237): threadid=10: thread exiting with uncaught exception (group=0x41675e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
D/Process (  906): killProcessQuiet, pid=2237
E/AndroidRuntime( 2237): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2237): Process: com.google.android.gms, PID: 2237
E/AndroidRuntime( 2237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2237): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2237): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2237): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2237): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2237): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2237): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2237): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  906): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  906): Killing 2237:com.google.android.gms/u0a28 (adj 6): crash
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
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
I/IcingCorporaProvider( 4486): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2906): Died!
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4504 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4516 uid=10031 gids={50031, 3003, 5012}
D/LocationManagerService(  906): getProviders()=[passive]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
D/Process (  906): killProcessQuiet, pid=4170
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 4170:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4170
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/ActivityManager(  906): Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexService: pid=4533 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/MultiDex( 4533): install
I/MultiDex( 4533): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4533): loading existing secondary dex files
I/MultiDex( 4533): load found 1 secondary dex files
I/MultiDex( 4533): install done
I/ProviderInstaller( 4533): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): acquireWL(425de368): PARTIAL_WAKE_LOCK  Icing 0x1 4533 10028 null
E/SQLiteDatabase( 4533): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4533): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4533): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4533): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4533): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:310)
E/SQLiteDatabase( 4533): 	at ijp.a(SourceFile:146)
E/SQLiteDatabase( 4533): 	at ijp.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4533): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4533): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4533): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4533): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4533): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4533): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4533): threadid=14: thread exiting with uncaught exception (group=0x41675e30)
E/AndroidRuntime( 4533): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 4533): Process: com.google.android.gms, PID: 4533
E/AndroidRuntime( 4533): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4533): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 4533): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4533): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4533): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4533): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4533): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4533): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4533): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 4533): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4533): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4533): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4533): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:310)
E/AndroidRuntime( 4533): 	at ijp.a(SourceFile:146)
E/AndroidRuntime( 4533): 	at ijp.doInBackground(SourceFile:143)
E/AndroidRuntime( 4533): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 4533): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4533): 	... 4 more
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
I/Icing   ( 4533): Storage manager: low false usage 1.49MB avail 7.46GB capacity 7.85GB
D/Process ( 4533): killProcess, pid=4533
D/Process ( 4533): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4533
D/PMS     (  906): handleWLDeath(425de368): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  906): Process com.google.android.gms (pid 4533) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
E/SQLiteDatabase( 4504): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4504): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4504): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4504): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4504): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4504): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4504): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4504): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4504): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4504): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4504): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4504): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4504): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4504): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4504): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4504): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4504): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4504): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4504): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4504): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4504): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4504): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4504): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4504): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4504): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4504): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4504): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4504): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4504): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4504): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4504): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4504): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4504): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4504): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4504): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4504): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4504): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4504): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4504): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4504): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4504): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4504): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4504): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4504): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4504): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4504): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4504): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4504): threadid=11: thread exiting with uncaught exception (group=0x41675e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4504): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4504): Process: com.google.android.apps.docs, PID: 4504
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
E/AndroidRuntime( 4504): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4504): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4504): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4504): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4504): 	at aho.run(AbstractDatabaseInstance.java:455)
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

```
