#### Test 58135655812b57f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1530): handler message = 4011
E/HtcModeClient( 1530): Check connection and retry 8 times.
,--------- beginning of /dev/log/system
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/HABCtrl (  909): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
E/cutils-trace( 4283): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4283): ====startRecUseTime====
D/htc.customization.log.level( 4283):  is 
W/CustomizationLogLevel( 4283): Level value is invalid, use default level 2
D/CustomizationManager( 4283):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4283): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4283): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4283): Parsing tag category name = system
I/CustomizationCIDLoader( 4283): Parsing tag category name = application
I/CustomizationCIDLoader( 4283): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4283): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4283): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4283): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4283): Parsing tag category name = Settings
D/CustomizationManager( 4283):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4283):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4283): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4283): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4283): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4283): Fail to get flag for type 'language', use default value: -1
I/ClockThread( 1120): now=1454948639856 next=144
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4283
I/ClockThread( 1120): now=1454948640000 next=60000
V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=70522, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
V/AlarmManager(  909): sending alarm PendingIntent{42dbb9b8: PendingIntentRecord{42cae1d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71062, Int=0
,I/GAV2    ( 4118): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(42e72278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42e72278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1530): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1530): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(42dc1de0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3859 10154 null
,I/ActivityManager(  909): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3859): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3859): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3859, uid=10154, userID:0
,I/MusicLeanback( 3859): Conditions not met for autocaching.
,I/MusicLeanback( 3859): Stop autocaching.
D/PMS     (  909): releaseWL(42dc1de0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4302 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4302): Loading default preferences
,W/Resources( 4302): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  909): New client listening to asynchronous messages
,D/SyncApplication( 4302): Overriding preferences with custom values
,D/SyncApplication( 4302): Updating preferences succeeded
,E/SyncApplication( 4302): Application created.
D/VolumeInfo( 4302): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4302): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4302): Found 0 mount point(s)
,V/VolumeInfo( 4302): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4302): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4302): getNewCalendarAuthority()...
,D/VolumeInfo( 4302): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4302): Can not create volume ID for unmounted volume null
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4302, uid=10008, userID:0
,D/SyncApplication( 4302): enableAppOperation()+
,D/SyncApplication( 4302): enableAppOperation()-
,D/HTCUtilities( 4302): isNeorSinged() + 
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4302, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4302): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4302): isNeorSinged() return false
,D/CDMountReceiver( 4302): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4302): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4302): enable CD Auto-mount: true
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4302): enable auto-mount
,D/HTCUtilities( 4302): enable auto-mount
,I/ActivityManager(  909): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  909): Resuming delayed broadcast
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42354748 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 1 13 3 11
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42354a90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 0 10 3 16
,W/MediaManager( 3841): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  909): killProcessQuiet, pid=3926
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3926:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3926
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42e10dc0 u0 com.htc.musicenhancer/.EnhancerService}
,W/ContextImpl( 4169): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/AdsMeasurementBroadcastReceiver( 2251): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2251): Unauthorized to start the main service
,D/ConnectivityService(  909): getAllNetworkInfo called by  (2449/10021)
,I/DownloadManager( 2449): Download 277 starting
D/PMS     (  909): acquireWL(42e97838): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2449 10021 WorkSource{10016}
D/ConnectivityService(  909): getAllNetworkInfo called by  (2449/10021)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2449/10021)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/ContextImpl( 4169): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WIFI_ICON( 1120): WifiActivity: 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  909): getAllNetworkInfo called by  (2449/10021)
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2449): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2449): Download 278 starting
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  909): acquireWL(4246e408): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2449 10021 WorkSource{10016}
D/ConnectivityService(  909): getAllNetworkInfo called by  (2449/10021)
,I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4330 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=87 rxSum=71} preTxRxSum={txSum=56 rxSum=39}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20179 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20180 delay=15s
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2449/10021)
,D/PMS     (  909): releaseWL(42eb1eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2449/10021)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2449): Ignoring Content-Length since Transfer-Encoding is also defined
,D/CalendarApplication( 4330): onCreate
D/ProviderChangeReceiver( 4330): ---------------------------------------------------
,D/ProviderChangeReceiver( 4330): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4330): start to updateAlertNotification!
,I/ActivityManager(  909): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4346 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  909): killProcessQuiet, pid=3902
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3902:com.htc.sdm/u0a80 (adj 15): empty #17
,D/AlertService( 4330): No fired or scheduled alerts
,D/HtcAlertUtils( 4330): -- cancelReminderNotification --
,D/HtcAlertUtils( 4330): broadcastExistReminder!
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2449/10021)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  909): Recipient 3902
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=3 [30][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,V/Settings:HtcSettingsApplication( 4346): [4346/4346] onCreate()
W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/DownloadManager( 2449): Download 277 finished with status SUCCESS
,D/PMS     (  909): releaseWL(42e97838): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DownloadManager( 2449): Download 278 finished with status SUCCESS
,W/ContextImpl( 4169): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
D/PMS     (  909): releaseWL(4246e408): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/UpdateFetcherService( 4169): Update downloaded, starting installation
,I/UpdateFetcherService( 4169): Started installation
I/ActivityManager(  909): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,W/ContextImpl( 4169): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4169): Update downloaded, starting installation
,I/UpdateFetcherService( 4169): Started installation
I/ActivityManager(  909): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Resuming delayed broadcast
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
,D/Process (  909): killProcessQuiet, pid=3952
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3952:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3952
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ConfigUpdateInstallReceiver(  909): Not installing, new version is <= current version
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 9 times.
,I/SensorManager(  909): mEventCount = 750
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/PackageSettings(  909): Skipping PackageSetting{42a9ea08 com.test.thalitest/10189} due to missing metadata
,D/PMS     (  909): releaseWL(428731e0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:160, mTXpacketCount:99, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 10 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/PMS     (  909): acquireWL(42ef37a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{42c247c0: PendingIntentRecord{42ddde70 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454948650198, Int=0
,D/PMS     (  909): releaseWL(42ef37a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4082): [1] 5.onFinished: Installation state replication succeeded.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1405): service - has update message, not stop
,D/AutoSetting( 1405): service - mHandler: update timezone
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1530): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1530): service - mHandler: update timezone
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1530): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1530): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{42355120 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 8 3 11
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 11 times.
,I/SensorManager(  909): mEventCount = 900
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=119 rxSum=102} preTxRxSum={txSum=87 rxSum=71}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20180 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20181 delay=15s
D/PMS     (  909): acquireWL(42f16280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42c2e4e8: PendingIntentRecord{42cae1d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88564, Int=0
D/PMS     (  909): releaseWL(42f16280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 12 times.
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:162, mTXpacketCount:160, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  909): acquireWL(42ee8c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ee8c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1530): Don't start project servcice
,D/HtcModeClient( 1530): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1530): connectState: CONNECTION_READY = false
D/SilentMusic( 1530): call stop
,D/HtcModeClient( 1530): close connection
W/HtcModeClient( 1530): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1530): read the terminate packet, so break
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/SensorManager(  909): mEventCount = 1050
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42e8a4a0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  909): acquireWL(42dfd460): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(42dfd460): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(42f06198): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(42f06198): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(42c99a40): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(42c99a40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(42be3718): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(42be3718): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=120 rxSum=103} preTxRxSum={txSum=119 rxSum=102}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20181 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20182 delay=15s
D/PMS     (  909): acquireWL(42e92ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42e2cfe8: PendingIntentRecord{42cae1d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103568, Int=0
D/PMS     (  909): releaseWL(42e92ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  909): acquireWL(42d9cea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{42ca71c8: PendingIntentRecord{42e25380 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454948657142, Int=563223000
,D/PMS     (  909): acquireWL(42e5c108): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4377 uid=10077 gids={50077}
,V/AlarmManager(  909): sending alarm PendingIntent{42d125d8: PendingIntentRecord{42d68ea8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454948674229, Int=60000
,D/PMS     (  909): releaseWL(42d9cea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): acquireWL(42e00a50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(42e5c108): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
I/CheckinService( 2251): Preparing to send checkin request
I/EventLogService( 2251): Accumulating logs since 1454948623197
,W/EventLogAggregator( 2251): Unknown tag: install_package_attempt
W/EventLogAggregator( 2251): Unknown tag: snet
,W/EventLogAggregator( 2251): Unknown tag: snet_gcore
,D/SMSBackup( 4377): SMSBackupAgentService started
,D/SMSBackup( 4377): Checking restore status
,D/SMSBackup( 4377): Restore complete
,D/SMSBackup( 4377): cancelCheckAlarm
,D/SMSBackup( 4377): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=3993
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3993:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3993
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GoogleHttpClient( 2251): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2251): Using GMS GoogleHttpClient
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1373): GoogleAccountDataService.getToken()
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1373): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{423bb990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 7 2 12
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4391 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4391): install
,I/MultiDex( 4391): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4391): loading existing secondary dex files
,I/MultiDex( 4391): load found 1 secondary dex files
,I/MultiDex( 4391): install done
,I/ProviderInstaller( 4391): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4391): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4391): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4391): Local Branch: 
I/Adreno-EGL( 4391): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4391): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4391):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4391): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4391): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4391): Local Branch: 
I/Adreno-EGL( 4391): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4391): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4391):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4391/10028)
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/Adreno-EGL( 4391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4391): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4391): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4391): Local Branch: 
I/Adreno-EGL( 4391): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4391): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4391):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4391): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 2251): Sending checkin request (9027 bytes)
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
,D/libc    ( 2251): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7624 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  909): acquireWL(42e5a148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10028 null
,D/PMS     (  909): releaseWL(42e5a148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [14][0][0],
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
,W/GLSUser ( 1373): GoogleAccountDataService.getToken()
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1373): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/CheckinRequestBuilder( 2251): awaiting user notification for token
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{424dc6c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 7 2 12
,I/CheckinTask( 2251): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2251): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  909): releaseWL(42e00a50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2251): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@424957c8 that was originally bound here
E/ActivityThread( 2251): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@424957c8 that was originally bound here
E/ActivityThread( 2251): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2251): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2251): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2251): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2251): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2251): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2251): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2251): 	at bks.a(SourceFile:298)
E/ActivityThread( 2251): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2251): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2251): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2251): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1373): GCM config loaded
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:176, mTXpacketCount:162, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  909): mEventCount = 1200
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  909): Going to sleep due to screen timeout...
,W/PMS     (  909): mWirelessDisplayManager is null
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@429bb020
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@429bb020, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42b792d0
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@4256d748
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/Process (  909): killProcessQuiet, pid=2778
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 2778:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 374ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
I/ActivityManager(  909): Recipient 2778
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=1271
,I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  909): OOBE c monitor 11
D/PMS     (  909): acquireWL(43080bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
,D/NfcService( 1259): applyRouting -2
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43081910)
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMN     (  909): wakingUp
D/PMS     (  909): releaseWL(43080bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  909): No lock screen! windowToken=null
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20183 delay=15s
D/PMN     (  909): onScreenOn
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
,D/MtpService( 2449): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1259): applyRouting - 0
,D/MtpService( 2449): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting -2
D/PMS     (  909): acquireWL(43088078): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:On
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1176): BG scan when screen On
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): Match BG scan, scan!
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  909):    returned true
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43088078): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/ClockThread( 1120): stop update clock
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4418 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800,
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  909): updateScreenOn: false
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  909): acquireWL(430987c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1425 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1814): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1814): onScreenOn: 1454948681019
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1814): onScreenOn: 1454948681019
,D/SmartSyncUtils( 4418): isEpsOn(), nState = 0
D/PMS     (  909): releaseWL(430987c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  909): acquireWL(43099698): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4418 1000 null
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42b792d0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42b792d0, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@4256d748
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
,I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
,I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4284fcd0
,I/SocialFeedProvider( 1271): +onPause
D/PMS     (  909): acquireWL(4309beb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43099698): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SocialFeedProvider( 1271): -onPause
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20183 mDataStallAlarmIntent=PendingIntent{42c5b0d0: PendingIntentRecord{42cae1d8 android broadcastIntent}}
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:Off
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1176): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(430a3068): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4309beb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  909): updateScreenOn: false
,D/SmartSyncUtils( 4418): getMobilePolicyEnabled, result = true
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  909): killProcessQuiet, pid=4036
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1405): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  909): Killing 4036:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 4140): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4140): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4140): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4140): Cust_ConnectToPC   : spcsc>false
D/        ( 4140): Cust_ConnectToPC   : IPT>true
,D/        ( 4140): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4140): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4140): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4140): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4140): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4140): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4140): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4140): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4140):  defaultType:0
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(430a3068): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4418): isEpsOn(), nState = 0
D/SmartSyncUtils( 4418): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4418): isEpsOn(), nState = 0
D/AutoSetting( 1405): service - mHandler: cancel location update
,D/AutoSetting( 1405): service -           changes count: 0
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiService(  909): New client listening to asynchronous messages
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1814): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1814): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1814): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1814): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1814): onScreenOff
D/PMS     (  909): acquireWL(430b8be8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1425 10028 null
D/PMS     (  909): releaseWL(430b8be8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4256d748
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4256d748, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
,W/SensorService(  909): Active sensors: size = 0
,W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4256d748, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Recipient 4036
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4256d748
,E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42bc73f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42bc73f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1530): service - handleMessage() stop self
,D/AutoSetting( 1530): service - onDestroy() END
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4212
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4212:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4212
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1176): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1176): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1176): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1176): Add randomness: count=11 e,ntropy=5
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: DISCONNECTED -> INACTIVE
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-47
I/wpa_supplicant( 1176): tsf=0000000022111023
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000114211503
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000114211515
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42dc4e40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@42dc4e40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@42dc4e40 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 22111023, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 114211503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 114211515, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/Process (  909): killProcessQuiet, pid=3881
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3881:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3881
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42f45100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42f45100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42f44e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1176): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1176): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1176): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 la,st_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1176): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1176): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1176): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
I/BatteryService(  909): n_update end
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42f44e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/HtcPowerSaver(  909): updateBatteryInfo
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000132453542
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000132453582
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-71
I/wpa_supplicant( 1176): tsf=0000000132453592
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000132453569
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 132453542, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 132453582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 132453592, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 132453569, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1405): service - handleMessage() stop self
D/PMS     (  909): acquireWL(427d2dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42911f10: PendingIntentRecord{42b5d678 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141676, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42372700: PendingIntentRecord{42d4ec70 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141699, Int=0
,D/AutoSetting( 1405): service - handleMessage() quit looper
,D/AutoSetting( 1405): service - onDestroy() END
,I/ActivityManager(  909): Killing 4243:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4243
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4243
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(42ced660): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1373/10028)
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/PMS     (  909): acquireWL(427f2710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10028 null
D/PMS     (  909): releaseWL(427d2dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): releaseWL(427f2710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c317 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(42ced660): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1176): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1176): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1176): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1176): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1176): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1176): Add randomness: count=27 entropy=21
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000150674963
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000150675000
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000000150675010
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000150674989
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 150674963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 150675000, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 150675010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 150674989, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter,
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1176): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1176): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1176): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1176): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1176): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1176): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000168991435
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000168991472
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000000168991482
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
,I/wpa_supplicant( 1176): tsf=0000000168991461
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 168991435, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 168991472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 168991482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 168991461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028),
,D/PMS     (  909): acquireWL(42ee0598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ee0598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e2ae58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{42c3bf98: PendingIntentRecord{42d1b418 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174078, Int=0
,D/PMS     (  909): releaseWL(42e2ae58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1176): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1176): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1176): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
,I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1176): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1176): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1176): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1,
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000187254674
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000187254712
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700,
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000000187254722
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000187254701
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 187254674, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 187254712, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 187254722, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 187254701, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults,
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42e51958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e51958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(430a2fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(430a2fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-86
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1176): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1176): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1176): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1176): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-86
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1176): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1176): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1176): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1176): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000187254674
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000205504899
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700,
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000000205504909
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000205504888
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-86
I/wpa_supplicant( 1176): tsf=0000000205504918
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 187254674, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 205504899, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 205504909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 205504888, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2462, timestamp: 205504918, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-86], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-86
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1176): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1176): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1176): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1176): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-86
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1176): Add randomness: count=60 entropy=54
,D/wpa_supplicant( 1176): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1176): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1176): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3,
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000223831561
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000223831598
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000223831609
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
,I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000223831587
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-86
I/wpa_supplicant( 1176): tsf=0000000223831617
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 223831561, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 223831598, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 223831609, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 223831587, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2462, timestamp: 223831617, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-86], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1176): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1176): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1176): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1176): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1176): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1176): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1176): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1176): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000242105178
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000242105216
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000242105226
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000242105205
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000242105234
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_su,pplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 242105178, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 242105216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 242105226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 242105205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 242105234, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42ecf4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ecf4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42e8ccf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42e8ccf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1176): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1176): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1176): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1176): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=79 entropy=73
,D/wpa_supplicant( 1176): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1176): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1176): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1176): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
,I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000260354787
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000260354824
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
,I/wpa_supplicant( 1176): tsf=0000000260354835
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000260354813
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000260354843
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 260354787, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 260354824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 260354835, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 260354813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 260354843, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1176): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1176): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1176): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1176): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1176): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1176): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1176): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1176): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000278670946
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000278670983
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000278670993
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000278670972
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000278671002
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 278670946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 278670983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 278670993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 278670972, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 278671002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  909): acquireWL(4307f320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4307f320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1176): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1176): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1176): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1176): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1176): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1176): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (631) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
,I/wpa_supplicant( 1176): tsf=0000000296895083
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000296895122
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000000296895132
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====,
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000296895109
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=4
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000278671002
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 296895083, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 296895122, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 296895132, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 296895109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 278671002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42f31878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=310522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42f31878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42f33310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/PMS     (  909): releaseWL(42f33310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1176): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1176): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1176): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used,=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1176): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1176): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1176): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000315094640
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000315094677
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412,
I/wpa_supplicant( 1176): level=-80
I/wpa_supplicant( 1176): tsf=0000000315094686
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000315094666
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 315094640, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 315094677, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 315094686, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 315094666, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1176): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1176): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1176): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1176): Add randomness: count=115 entropy=109
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplic,ant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  909): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000333431986
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000333432012
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-80
I/wpa_supplicant( 1176): tsf=0000000333432023
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000315094666
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 333431986, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 333432012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 333432023, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 315094666, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1176): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1176): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1176): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1176): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1176): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1176): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1176): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000351675854
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000351675892
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-75
I/wpa_supplicant( 1176): tsf=0000000351675902
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000351675880
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 351675854, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 351675892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 351675902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 351675880, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43018ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43018ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1373): GoogleAccountDataService.getToken()
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1373): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1373): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1373): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1373): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1373): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1373): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1373): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1373): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1373): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1373): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/PlayEventLogger( 4082): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4082): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4082): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4082): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4082): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4082): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4082): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4082): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{423bb990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 9 3 12
,D/libc    ( 4082): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4082): [NET] getaddrinfo-,err=8
D/libc    ( 4082): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4082): [NET] getaddrinfo-, 1
,D/libc    ( 4082): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3459 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =,
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4082): [NET] getaddrinfo_proxy-, success
I/global  ( 4082): call createSocket() return a new socket.
D/libc    ( 4082): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4082): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4082): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4082): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1176): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1176): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1176): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1176): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1176): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1176): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1176): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000369782114
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000369782151
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-75
I/wpa_supplicant( 1176): tsf=0000000369782161
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000369782140
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 369782114, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 369782151, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 369782161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 369782140, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430cba00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=370522, Int=0,
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(430cba00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(430cd478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(430cd478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1176): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1176): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1176): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1176): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1176): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1176): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps,=0x511
D/wpa_supplicant( 1176): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1176): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1176): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1176): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1176): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1176): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1176): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (902) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000388044800
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000388044836
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000388044848
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000388044825
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
,I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000388044867
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=6
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000388044857
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=7
I/wpa_supplicant( 1176): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1176): freq=2437
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000000388044878
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=UPC4688432
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 388044800, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 388044836, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 388044848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 388044825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 388044867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 388044857, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 388044878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1176): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1176): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1176): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1176): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1176): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/,WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1176): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1176): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1176): Add randomness: count=155 entropy=149
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1176): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1176): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (902) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
,I/wpa_supplicant( 1176): tsf=0000000406351856
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000406351883
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000406351895
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000388044825
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
,I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000406351917
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=6
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000406351904
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=7
I/wpa_supplicant( 1176): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1176): freq=2437
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000000406351928
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1176): ssid=UPC4688432
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 406351856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 406351883, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 406351895, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 388044825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 406351917, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 406351904, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 406351928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
,I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1176): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1176): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1176): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1176): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1176): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1,
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1176): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1176): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1176): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1176): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1176): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (789) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000424604715
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000424604742
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000424604753
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000424604771
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=6
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000424604761
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=7
I/wpa_supplicant( 1176): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1176): freq=2437
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000000424604780
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=UPC4688432
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 424604715, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 424604742, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 424604753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 424604771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 424604761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 424604780, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4452 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  909): acquireWL(43130d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10047}
,V/AlarmManager(  909): sending alarm PendingIntent{42cfe4b8: PendingIntentRecord{42cff3b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454948790081, Int=10800000,
V/AlarmManager(  909): sending alarm PendingIntent{42e88660: PendingIntentRecord{42e7fe90 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1454948925683, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42d7b280: PendingIntentRecord{42b83b60 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454948994728, Int=1800000
,D/PMS     (  909): acquireWL(43135098): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(43130d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): acquireWL(43136ac8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2251 10028 null
,D/PMS     (  909): releaseWL(43135098): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2251): Aggregate from 1454948674282 (log), 1454947194668 (data)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4452/10047)
,D/PMS     (  909): releaseWL(43136ac8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/Process (  909): killProcessQuiet, pid=4118
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4118:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4118
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Uploader( 2251): No account for auth token provided
,D/libc    ( 2251): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
,D/libc    ( 2251): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =95e0 +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
I/global  ( 2251): call createSocket() return a new socket.
D/libc    ( 2251): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2251): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/PMS     (  909): acquireWL(43149360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=430522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43149360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4314adf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4314adf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1176): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1176): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes),
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
,I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1176): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1176): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (789) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000442824749
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
,I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000442824775
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000442824786
,I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000424604771
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=6
,I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000424604761
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=7
I/wpa_supplicant( 1176): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1176): freq=2437
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000000424604780
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=UPC4688432
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 442824749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 442824775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 442824786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 424604771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 424604761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 424604780, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==,
,D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1176): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1176): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1176): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/w,pa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1176): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1176): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1176): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000461042037
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000461042063
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000461042075
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000461042084
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 461042037, distance: ?(cm), distanceSd: ?(cm),
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 461042063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 461042075, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 461042084, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==,
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(43138ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43138ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1176): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1176): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1176): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1176): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1176): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1176): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000479294804
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000479294830
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
,I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000479294841
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000479294850
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 479294804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 479294830, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 479294841, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 479294850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f1ef68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=490523, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42f1ef68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42f1ec70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f1ec70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1176): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1176): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1176): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/w,pa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1176): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1176): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1176): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000497323110
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g,
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000497323137
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000497323148
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000479294850
,I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 497323110, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 497323137, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 497323148, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 479294850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1176): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1176): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1176): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_sup,plicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1176): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1176): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1176): Add randomness: count=207 entropy=201
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000515322140
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000515322165
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000515322177
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000479294850
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 515322140, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 515322165, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 515322177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 479294850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42e8a6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42e8a6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1176): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1176): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1176): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/w,pa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1176): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1176): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1176): Add randomness: count=215 entropy=209
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000533671625
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000533671651
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
,I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000533671661
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000479294850
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 533671625, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 533671651, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 533671661, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 479294850, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42da5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=550523, Int=0,
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42da5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1176): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1176): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
,I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3,
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=219 entropy=213
,D/wpa_supplicant( 1176): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1176): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (518) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000551894874
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000551894901
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-80
I/wpa_supplicant( 1176): tsf=0000000551894912
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=5
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000479294850
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 551894874, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 551894901, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 551894912, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 479294850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42d68478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42d68478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1176): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1176): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1176): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1176): Add randomness: count=227 entro,py=221
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000570191965
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000570191991
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000570192003
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 570191965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 570191991, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 570192003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1,
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1176): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1176): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=231 entropy=225
D/wpa_supplicant( 1176): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1176): Add randomness: count=233 entro,py=227
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987,
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000588411784
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000588411810
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000588411824
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 588411784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 588411810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 588411824, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76,
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1176): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1176): Add randomness: count=236 entropy=230,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
,I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
,I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1176): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1176): Add randomness: count=239 entropy=233
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000606403398
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000606403424
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000606403435
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 606403398, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 606403424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 606403435, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4311f0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=610522, Int=0,
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4311f0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  909): acquireWL(4316dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(4316dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1247): sku_id=99
D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1247): start background delete task...,
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=240 entropy=234
D/wpa_supplicant( 1176): Add randomness: count=241 entropy=235
D/wpa_supplicant( 1176): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=243 entropy=237
D/wpa_supplicant( 1176): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1176): Add randomness: count=245 entro,py=239
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000606403398
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000624644665
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000624644676
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 606403398, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 624644665, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 624644676, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1176): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1176): Add randomness: count=248 entropy=242,
D/wpa_supplicant( 1176): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1176): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1176): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1176): Add randomness: count=253 entropy=247
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
,W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000642971762
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000642971800
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000642971810
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000642971788
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 642971762, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 642971800, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 642971810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 642971788, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults,
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1176): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1176): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1176): Add randomness: count=257 entropy=251
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1176): Add randomness: count=259 entropy=253
D/wpa_supplicant( 1176): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1176): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000661224757
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000661224793
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000661224803
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000661224782
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 661224757, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 661224793, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 661224803, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 661224782, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/Process (  909): killProcessQuiet, pid=3627
,I/ActivityManager(  909): Killing 3627:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3627
,D/PMS     (  909): acquireWL(42e03c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=670522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e03c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ef9750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42ef9750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4140): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4140): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4140): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4140): Cust_ConnectToPC   : spcsc>false
D/        ( 4140): Cust_ConnectToPC   : IPT>true
,D/        ( 4140): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4140): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4140): Index of the first 1 = 3
,W/Settings( 4140): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4140): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4140): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/SmartNS_NSReceiver( 4140): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4140): [ACC]android_networking:tethering_guard_support=false
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1176): Add randomness: count=263 entropy=257
D/wpa_supplicant( 1176): Add randomness: count=264 entropy=258
D/wpa_supplicant( 1176): Add randomness: count=265 entropy=259
D/wpa_supplicant( 1176): Add randomness: count=266 entropy=260
D/wpa_supplicant( 1176): Add randomness: count=267 entropy=261
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=268 entropy=262
D/wpa_supplicant( 1176): Add randomness: count=269 entropy=263
D/wpa_supplicant( 1176): Add randomness: count=270 entropy=264
D/wpa_supplicant( 1176): Add randomness: count=271 entropy=265
D/wpa_supplicant( 1176): Add randomness: count=272 entropy=266
D/wpa_supplicant( 1176): Add randomness: count=273 entropy=267
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (756) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000679484879
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000679484916
,I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-75
I/wpa_supplicant( 1176): tsf=0000000679484926
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000679484905
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=9
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000679484935
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000679484945
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 679484879, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 679484916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 679484926, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 679484905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 679484935, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 679484945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=274 entropy=268
D/wpa_supplicant( 1176): Add randomness: count=275 entropy=269
D/wpa_supplicant( 1176): Add randomness: count=276 entropy=270
D/wpa_supplicant( 1176): Add randomness: count=277 entropy=271
D/wpa_supplicant( 1176): Add randomness: count=278 entropy=272
D/wpa_supplicant( 1176): Add randomness: count=279 entropy=273
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=280 entropy=274
D/wpa_supplicant( 1176): Add randomness: count=281 entropy=275
D/wpa_supplicant( 1176): Add randomness: count=282 entropy=276
D/wpa_supplicant( 1176): Add randomness: count=283 entropy=277
D/wpa_supplicant( 1176): Add randomness: count=284 entropy=278
D/wpa_supplicant( 1176): Add randomness: count=285 entropy=279
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
,I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (756) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000679484879
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000697811400
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-75
I/wpa_supplicant( 1176): tsf=0000000697811410
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000697811389
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=9
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000697811419
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000697811429
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 679484879, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 697811400, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 697811410, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 697811389, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 697811419, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 697811429, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f05540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end,
,D/PMS     (  909): releaseWL(42f05540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-,
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=286 entropy=280
D/wpa_supplicant( 1176): Add randomness: count=287 entropy=281
D/wpa_supplicant( 1176): Add randomness: count=288 entropy=282
D/wpa_supplicant( 1176): Add randomness: count=289 entropy=283
D/wpa_supplicant( 1176): Add randomness: count=290 entropy=284
D/wpa_supplicant( 1176): Add randomness: count=291 entropy=285
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=292 entropy=286
D/wpa_supplicant( 1176): Add randomness: count=293 entropy=287
D/wpa_supplicant( 1176): Add randomness: count=294 entropy=288
D/wpa_supplicant( 1176): Add randomness: count=295 entropy=289
D/wpa_supplicant( 1176): Add randomness: count=296 entropy=290
D/wpa_supplicant( 1176): Add randomness: count=297 entropy=291
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (756) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000716054839
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000716054877
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700,
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000716054887
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000716054866
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=9
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
,I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000716054895
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000716054905
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 716054839, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 716054877, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 716054887, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 716054866, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 716054895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 716054905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (6) end of scan result ==,
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43089138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=730523, Int=0,
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43089138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  909): acquireWL(42f5b470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f5b470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=298 entropy=292
D/wpa_supplicant( 1176): Add randomness: count=299 entropy=293
D/wpa_supplicant( 1176): Add randomness: count=300 entropy=294
D/wpa_supplicant( 1176): Add randomness: count=301 entropy=295
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=302 entropy=296
D/wpa_supplicant( 1176): Add randomness: count=303 entropy=297
D/wpa_supplicant( 1176): Add randomness: count=304 entropy=298
D/wpa_supplicant( 1176): Add randomness: count=305 entropy=299
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (756) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000734322779
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000734322816
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000734322825
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000734322805
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=9
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000716054895
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000716054905
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 734322779, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 734322816, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 734322825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 734322805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 716054895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 716054905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (6) end of scan result ==,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=306 entropy=300
,D/wpa_supplicant( 1176): Add randomness: count=307 entropy=301
D/wpa_supplicant( 1176): Add randomness: count=308 entropy=302
D/wpa_supplicant( 1176): Add randomness: count=309 entropy=303
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
,I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
,I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=310 entropy=304
D/wpa_supplicant( 1176): Add randomness: count=311 entropy=305
D/wpa_supplicant( 1176): Add randomness: count=312 entropy=306
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): Add randomness: count=313 entropy=307
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (632) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000752614764
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000752614790
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000752614801
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=8
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000734322805
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000752614810
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 752614764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 752614790, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 752614801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 734322805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 752614810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(430928e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(430928e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=314 entropy=308
D/wpa_supplicant( 1176): Add randomness: count=315 entropy=309
D/wpa_supplicant( 1176): Add randomness: count=316 entropy=310
D/wpa_supplicant( 1176): Add randomness: count=317 entropy=311
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/w,pa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=318 entropy=312
D/wpa_supplicant( 1176): Add randomness: count=319 entropy=313
D/wpa_supplicant( 1176): Add randomness: count=320 entropy=314
D/wpa_supplicant( 1176): Add randomness: count=321 entropy=315
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (519) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000770891947
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000770891973
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
,I/wpa_supplicant( 1176): tsf=0000000770891984
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000770891993
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 770891947, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 770891973, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 770891984, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 770891993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=322 entropy=316
D/wpa_supplicant( 1176): Add randomness: count=323 entropy=317
D/wpa_supplicant( 1176): Add randomness: count=324 entropy=318
D/wpa_supplicant( 1176): Add randomness: count=325 entropy=319
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/w,pa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=326 entropy=320
D/wpa_supplicant( 1176): Add randomness: count=327 entropy=321
D/wpa_supplicant( 1176): Add randomness: count=328 entropy=322
D/wpa_supplicant( 1176): Add randomness: count=329 entropy=323
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (519) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000770891947
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000789162093
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
,I/wpa_supplicant( 1176): tsf=0000000789162104
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000789162113
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 770891947, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 789162093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 789162104, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 789162113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(431430f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=790522, Int=0,
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431430f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42fc8190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42fc8190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1176): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=330 entropy=324
D/wpa_supplicant( 1176): Add randomness: count=331 entropy=325
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1176): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=332 entropy=326
D/wpa_supplicant( 1176): Add randomness: count=333 entropy=327
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA ,subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (519) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000807384873
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000807384899
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000789162104
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=10
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000789162113
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 807384873, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 807384899, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 789162104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 789162113, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter,
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=334 entropy=328
D/wpa_supplicant( 1176): Add randomness: count=335 entropy=329
D/wpa_supplicant( 1176): Add randomness: count=336 entropy=330
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=337 entropy=331
D/wpa_supplicant( 1176): Add randomness: count=338 entropy=332
D/wpa_supplicant( 1176): Add randomness: count=339 entro,py=333
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000825741952
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000825741978,
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000825741989
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 825741952, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 825741978, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 825741989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42ff96b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42ff96b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=340 entropy=334
D/wpa_supplicant( 1176): Add randomness: count=341 entropy=335
D/wpa_supplicant( 1176): Add randomness: count=342 entropy=336
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
,W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0,
D/wpa_supplicant( 1176): Add randomness: count=343 entropy=337
D/wpa_supplicant( 1176): Add randomness: count=344 entropy=338
D/wpa_supplicant( 1176): Add randomness: count=345 entropy=339
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000825741952
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000843984653
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000843984664
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 825741952, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 843984653, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 843984664, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4315fed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=850522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4315fed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43161988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43161988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=346 entropy=340
D/wpa_supplicant( 1176): Add randomness: count=347 entropy=341
D/wpa_supplicant( 1176): Add randomness: count=348 entropy=342
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=349 entropy=343
D/wpa_supplicant( 1176): Add randomness: count=350 entropy=344
D/wpa_supplicant( 1176): Add randomness: count=351 entro,py=345
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000862265062
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000862265089
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000862265100
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 862265062, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 862265089, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 862265100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=352 entropy=346
D/wpa_supplicant( 1176): Add randomness: count=353 entropy=347
D/wpa_supplicant( 1176): Add randomness: count=354 entropy=348
D/wpa_supplicant( 1176): Add randomness: count=355 entropy=349
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_sup,plicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=356 entropy=350
D/wpa_supplicant( 1176): Add randomness: count=357 entropy=351
D/wpa_supplicant( 1176): Add randomness: count=358 entropy=352
D/wpa_supplicant( 1176): Add randomness: count=359 entropy=353
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES,
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (490) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000862265062
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000880591214
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-84
I/wpa_supplicant( 1176): tsf=0000000880591224
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=11
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
,I/wpa_supplicant( 1176): tsf=0000000880591202
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 862265062, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 880591214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 880591224, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 880591202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42fb42c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PowerUI ( 1120): closing low battery warning: level=100
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42fb42c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=360 entropy=354
D/wpa_supplicant( 1176): Add randomness: count=361 entropy=355
D/wpa_supplicant( 1176): Add randomness: count=362 entropy=356
D/wpa_supplicant( 1176): Add randomness: count=363 entropy=357
D/wpa_supplicant( 1176): Add randomness: count=364 entropy=358
D/wpa_supplicant( 1176): Add randomness: count=365 entropy=359
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=366 entropy=360
D/wpa_supplicant( 1176): Add randomness: count=367 entropy=361
D/wpa_supplicant( 1176): Add randomness: count=368 entropy=362
D/wpa_supplicant( 1176): Add randomness: count=369 entropy=363
D/wpa_supplicant( 1176): Add randomness: count=370 entropy=364
D/wpa_supplicant( 1176): Add randomness: count=371 entropy=365
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (758) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000898804706
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000898804745
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-84
I/wpa_supplicant( 1176): tsf=0000000898804755
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=11
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000000898804734
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=12
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-88
I/wpa_supplicant( 1176): tsf=0000000898804763
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====,
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-92
I/wpa_supplicant( 1176): tsf=0000000898804773
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 898804706, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 898804745, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 898804755, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 898804734, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 898804763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 898804773, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList,
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42fe9cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=910522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42fe9cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42feb7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42feb7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=372 entropy=366
D/wpa_supplicant( 1176): Add randomness: count=373 entropy=367
D/wpa_supplicant( 1176): Add randomness: count=374 entropy=368
D/wpa_supplicant( 1176): Add randomness: count=375 entropy=369
D/wpa_supplicant( 1176): Add randomness: count=376 entropy=370
D/wpa_supplicant( 1176): Add randomness: count=377 entropy=371
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=378 entropy=372
D/wpa_supplicant( 1176): Add randomness: count=379 entropy=373
D/wpa_supplicant( 1176): Add randomness: count=380 entropy=374
D/wpa_supplicant( 1176): Add randomness: count=381 entropy=375
D/wpa_supplicant( 1176): Add randomness: count=382 entropy=376
D/wpa_supplicant( 1176): Add randomness: count=383 entropy=377
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (758) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000917054926
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
,I/wpa_supplicant( 1176): tsf=0000000917054964
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000917054974
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=11
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000000917054953
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=12
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000917054993
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
,I/wpa_supplicant( 1176): tsf=0000000917054983
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 917054926, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 917054964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 917054974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 917054953, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 917054993, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 917054983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (6) end of scan result ==,
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=384 entropy=378
D/wpa_supplicant( 1176): Add randomness: count=385 entropy=379
D/wpa_supplicant( 1176): Add randomness: count=386 entropy=380
D/wpa_supplicant( 1176): Add randomness: count=387 entropy=381
D/wpa_supplicant( 1176): Add randomness: count=388 entropy=382
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_sup,plicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=389 entropy=383
D/wpa_supplicant( 1176): Add randomness: count=390 entropy=384
D/wpa_supplicant( 1176): Add randomness: count=391 entropy=385
D/wpa_supplicant( 1176): Add randomness: count=392 entropy=386
D/wpa_supplicant( 1176): Add randomness: count=393 entropy=387
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (758) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000935275117
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000935275143
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000935275154
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=11
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000000917054953
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=12
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000935275172
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000935275163
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ####
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 935275117, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 935275143, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 935275154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 917054953, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 935275172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 935275163, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 6 to mScanResults,
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f447f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f447f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=394 entropy=388
D/wpa_supplicant( 1176): Add randomness: count=395 entropy=389
D/wpa_supplicant( 1176): Add randomness: count=396 entropy=390
D/wpa_supplicant( 1176): Add randomness: count=397 entropy=391
D/wpa_supplicant( 1176): Add randomness: count=398 entropy=392
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_sup,plicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1176): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=399 entropy=393
D/wpa_supplicant( 1176): Add randomness: count=400 entropy=394
D/wpa_supplicant( 1176): Add randomness: count=401 entropy=395
D/wpa_supplicant( 1176): Add randomness: count=402 entropy=396
D/wpa_supplicant( 1176): Add randomness: count=403 entropy=397
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (644) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000953541292
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000953541319
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-76
I/wpa_supplicant( 1176): tsf=0000000953541330
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=12
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000953541348
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000953541338
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 953541292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 953541319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 953541330, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 953541348, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 953541338, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(427744f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=970522, Int=0
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427744f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=404 entropy=398
D/wpa_supplicant( 1176): Add randomness: count=405 entropy=399
D/wpa_supplicant( 1176): Add randomness: count=406 entropy=400
D/wpa_supplicant( 1176): Add randomness: count=407 entropy=401
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=408 entropy=402
D/wpa_supplicant( 1176): Add randomness: count=409 entropy=403
D/wpa_supplicant( 1176): Add randomness: count=410 entropy=404
D/wpa_supplicant( 1176): Add randomness: count=411 entropy=405
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (758) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000953541292
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000971764713
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-74
I/wpa_supplicant( 1176): tsf=0000000953541330
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=12
I/wpa_supplicant( 1176): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-89
I/wpa_supplicant( 1176): tsf=0000000953541348
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC0039325
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-90
I/wpa_supplicant( 1176): tsf=0000000953541338
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000000971764701
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 953541292, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 971764713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 953541330, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 953541348, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 953541338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 971764701, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 6 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (6) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42c21b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): releaseWL(42c21b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=412 entropy=406
D/wpa_supplicant( 1176): Add randomness: count=413 entropy=407
D/wpa_supplicant( 1176): Add randomness: count=414 entropy=408
D/wpa_supplicant( 1176): Add randomness: count=415 entropy=409
D/wpa_supplicant( 1176): Add randomness: count=416 entropy=410
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=417 entropy=411
D/wpa_supplicant( 1176): Add randomness: count=418 entropy=412
D/wpa_supplicant( 1176): Add randomness: count=419 entropy=413
D/wpa_supplicant( 1176): Add randomness: count=420 entropy=414
D/wpa_supplicant( 1176): Add randomness: count=421 entropy=415
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (615) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000990004789
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000000990004826
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000990004836
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000000990004844
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000000990004814
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 990004789, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 990004826, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 990004836, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 990004844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 990004814, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42cf89e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
V/AlarmManager(  909): sending alarm PendingIntent{425d9cc8: PendingIntentRecord{42c67c58 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784140, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{428e3910: PendingIntentRecord{42ba9fb8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928886, Int=0
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..,
V/AlarmManager(  909): sending alarm PendingIntent{4255b918: PendingIntentRecord{42cc93e0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=994528, Int=0,
V/AlarmManager(  909): sending alarm PendingIntent{428fbf50: PendingIntentRecord{426b8430 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454949510383, Int=900000
,D/PMS     (  909): acquireWL(42df6a08): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1373 10028 null
,D/PMS     (  909): releaseWL(42df6a08): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
D/PMS     (  909): acquireWL(42b30d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10028 null
,D/PMS     (  909): acquireWL(42c12d58): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(42b30d30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): acquireWL(42f91cf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): releaseWL(42cf89e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4418): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4418): MY_DEBUG = false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=5 [127][7][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42d34b40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 909 1000 WorkSource{10160}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,I/ActivityManager(  909): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=4494 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  909): releaseWL(42c12d58): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42f91cf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f04930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42f04930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/dalvikvm-heap(  909): Grow heap (frag case) to 17.753MB for 148756-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43134b60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): releaseWL(43134b60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(42f1f3e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4494 10160 null
,D/PMS     (  909): acquireWL(42d299c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4494 10160 null
,D/PMS     (  909): releaseWL(42f1f3e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4494/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4494/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42991a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42d34b40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  909): releaseWL(42991a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): releaseWL(42d299c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=3859
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3859:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3859
,D/MediaRouterService(  909): Client com.google.android.music (pid 3859): Died!
,D/PMS     (  909): acquireWL(42941e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10028 null
,D/GCM     ( 1373): Message class mow
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1373/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1373/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1373/10028)
D/PMS     (  909): releaseWL(42941e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(42b7d930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10028 null
D/PMS     (  909): releaseWL(42b7d930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=422 entropy=416
D/wpa_supplicant( 1176): Add randomness: count=423 entropy=417
D/wpa_supplicant( 1176): Add randomness: count=424 entropy=418
D/wpa_supplicant( 1176): Add randomness: count=425 entropy=419
D/wpa_supplicant( 1176): Add randomness: count=426 entropy=420
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplican,t( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=427 entropy=421
D/wpa_supplicant( 1176): Add randomness: count=428 entropy=422
D/wpa_supplicant( 1176): Add randomness: count=429 entropy=423
D/wpa_supplicant( 1176): Add randomness: count=430 entropy=424
D/wpa_supplicant( 1176): Add randomness: count=431 entropy=425
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (615) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001008234784
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001008234821
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000001008234831
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000001008234840
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000001008234810
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1008234784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1008234821, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1008234831, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1008234840, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1008234810, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f1d6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f1d6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42f80ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/SmartSyncUtils( 4418): isEpsOn(), nState = 0
V/AlarmManager(  909): sending alarm PendingIntent{425dc6c8: PendingIntentRecord{430a6790 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454949581163, Int=0
D/PMS     (  909): releaseWL(42f80ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): acquireWL(430386a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4418 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4418): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4418): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4418): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4418): SettingOnTime = 1454979600000, randomSettingOnTime = 1454976300000
,D/SmartSyncScreenOnOffTimeReceiver( 4418): SettingOffTime = 1454976000000, randomSettingOffTime = 1454976000000
,D/SmartSyncScreenOnOffTimeReceiver( 4418): bDayMode = false,
D/SmartSyncScreenOnOffTimeReceiver( 4418): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4418): bNightModeTurnOffOnce = false
D/PMS     (  909): releaseWL(430386a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42ec81a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4255b918: PendingIntentRecord{42cc93e0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1024614, Int=0
,D/PMS     (  909): acquireWL(4309c690): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(42ec81a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42edbd98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null,
,D/PMS     (  909): releaseWL(4309c690): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42edbd98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=432 entropy=426
D/wpa_supplicant( 1176): Add randomness: count=433 entropy=427
D/wpa_supplicant( 1176): Add randomness: count=434 entropy=428
D/wpa_supplicant( 1176): Add randomness: count=435 entropy=429
D/wpa_supplicant( 1176): Add randomness: count=436 entropy=430
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
,D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
,I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1176): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1176): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=437 entropy=431
D/wpa_supplicant( 1176): Add randomness: count=438 entropy=432
D/wpa_supplicant( 1176): Add randomness: count=439 entropy=433
,D/wpa_supplicant( 1176): Add randomness: count=440 entropy=434
D/wpa_supplicant( 1176): Add randomness: count=441 entropy=435
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
,I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (615) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001026342564
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001026342601
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2,
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000001026342612
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000001026342620
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000001026342589
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1026342564, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1026342601, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1026342612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1026342620, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1026342589, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430ee6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1030522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(430ee6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43002390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43002390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=442 entropy=436
D/wpa_supplicant( 1176): Add randomness: count=443 entropy=437
D/wpa_supplicant( 1176): Add randomness: count=444 entropy=438
D/wpa_supplicant( 1176): Add randomness: count=445 entropy=439
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_sup,plicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=446 entropy=440
D/wpa_supplicant( 1176): Add randomness: count=447 entropy=441
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1176): Add randomness: count=448 entropy=442
D/wpa_supplicant( 1176): Add randomness: count=449 entropy=443
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (615) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001026342564
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001044574730
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000001044574740
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=13
I/wpa_supplicant( 1176): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1176): freq=2462
I/wpa_supplicant( 1176): level=-91
I/wpa_supplicant( 1176): tsf=0000001026342620
I/wpa_supplicant( 1176): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=UPC Wi-Free
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000001044574720
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1026342564, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1044574730, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1044574740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1026342620, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1044574720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=450 entropy=444
D/wpa_supplicant( 1176): Add randomness: count=451 entropy=445
D/wpa_supplicant( 1176): Add randomness: count=452 entropy=446
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1,
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=453 entropy=447
D/wpa_supplicant( 1176): Add randomness: count=454 entropy=448
D/wpa_supplicant( 1176): Add randomness: count=455 entropy=449
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
,I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (490) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-45
I/wpa_supplicant( 1176): tsf=0000001062971494
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001062971519
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001062971530
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=14
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-57
I/wpa_supplicant( 1176): tsf=0000001044574720
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1062971494, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1062971519, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1062971530, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1044574720, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f24168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f24168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results,
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1176): Add randomness: count=456 entropy=450
D/wpa_supplicant( 1176): Add randomness: count=457 entropy=451
D/wpa_supplicant( 1176): Add randomness: count=458 entropy=452
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
,D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=459 entropy=453
D/wpa_supplicant( 1176): Add randomness: count=460 entropy=454,
D/wpa_supplicant( 1176): Add randomness: count=461 entropy=455
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
,I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001081214704
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001081214730
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001081214742
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1081214704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1081214730, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1081214742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f72cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1090522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  909): releaseWL(42f72cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  909): acquireWL(42f37dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f37dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=462 entropy=456
D/wpa_supplicant( 1176): Add randomness: count=463 entropy=457
D/wpa_supplicant( 1176): Add randomness: count=464 entropy=458
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
,I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=465 entropy=459,
D/wpa_supplicant( 1176): Add randomness: count=466 entropy=460
D/wpa_supplicant( 1176): Add randomness: count=467 entropy=461,
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001099434833
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001099434859
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001099434870
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1099434833, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1099434859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1099434870, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available,
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=468 entropy=462
D/wpa_supplicant( 1176): Add randomness: count=469 entropy=463
D/wpa_supplicant( 1176): Add randomness: count=470 entropy=464
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
,D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=471 entropy=465
D/wpa_supplicant( 1176): Add randomness: count=472 entropy=466
D/wpa_supplicant( 1176): Add randomness: count=473 entropy=467
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001117772030
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001117772056
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
,I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001117772067
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1117772030, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1117772056, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1117772067, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42feb6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42feb6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=474 entropy=468
D/wpa_supplicant( 1176): Add randomness: count=475 entropy=469
D/wpa_supplicant( 1176): Add randomness: count=476 entropy=470
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=477 entropy=471
D/wpa_supplicant( 1176): Add randomness: count=478 entropy=472
D/wpa_supplicant( 1176): Add randomness: count=479 entro,py=473
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001136024629
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001136024655
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-71
I/wpa_supplicant( 1176): tsf=0000001136024667
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1136024629, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1136024655, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 1136024667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42ff1970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1150522, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ff1970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  909): acquireWL(42ff7090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42ff7090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=480 entropy=474
D/wpa_supplicant( 1176): Add randomness: count=481 entropy=475
D/wpa_supplicant( 1176): Add randomness: count=482 entropy=476
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=483 entropy=477
D/wpa_supplicant( 1176): Add randomness: count=484 entropy=478
D/wpa_supplicant( 1176): Add randomness: count=485 entro,py=479
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001136024629
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
,I/wpa_supplicant( 1176): tsf=0000001154312451
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-71
I/wpa_supplicant( 1176): tsf=0000001154312462
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1136024629, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1154312451, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 1154312462, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults,
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=486 entropy=480
D/wpa_supplicant( 1176): Add randomness: count=487 entropy=481
D/wpa_supplicant( 1176): Add randomness: count=488 entropy=482
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=489 entropy=483
D/wpa_supplicant( 1176): Add randomness: count=490 entropy=484
D/wpa_supplicant( 1176): Add randomness: count=491 entro,py=485
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001172621988
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001172622015
,I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-71
I/wpa_supplicant( 1176): tsf=0000001172622026
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1172621988, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1172622015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 1172622026, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(4302e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4302e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=492 entropy=486
D/wpa_supplicant( 1176): Add randomness: count=493 entropy=487
D/wpa_supplicant( 1176): Add randomness: count=494 entropy=488
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=495 entropy=489
D/wpa_supplicant( 1176): Add randomness: count=496 entropy=490
D/wpa_supplicant( 1176): Add randomness: count=497 entro,py=491
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001190831921
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001190831947
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001190831959
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1190831921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1190831947, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1190831959, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=498 entropy=492
D/wpa_supplicant( 1176): Add randomness: count=499 entropy=493
D/wpa_supplicant( 1176): Add randomness: count=500 entropy=494
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=501 entropy=495
D/wpa_supplicant( 1176): Add randomness: count=502 entropy=496
D/wpa_supplicant( 1176): Add randomness: count=503 entro,py=497
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001208942152,
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001208942179
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
,I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001208942190
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1208942152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1208942179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1208942190, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f92460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1210523, Int=0,
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  909): releaseWL(42f92460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42f93f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f93f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=504 entropy=498
D/wpa_supplicant( 1176): Add randomness: count=505 entropy=499
D/wpa_supplicant( 1176): Add randomness: count=506 entropy=500
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
,I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
,I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=507 entropy=501
D/wpa_supplicant( 1176): Add randomness: count=508 entropy=502
D/wpa_supplicant( 1176): Add randomness: count=509 entropy=503
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
,W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001227211984
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001227212009
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001227212020
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1227211984, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1227212009, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1227212020, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=510 entropy=504
D/wpa_supplicant( 1176): Add randomness: count=511 entropy=505
D/wpa_supplicant( 1176): Add randomness: count=512 entropy=506
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=513 entropy=507
D/wpa_supplicant( 1176): Add randomness: count=514 entropy=508
D/wpa_supplicant( 1176): Add randomness: count=515 entro,py=509
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
,I/wpa_supplicant( 1176): tsf=0000001245371786
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001245371813
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2,
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001245371824
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1245371786, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1245371813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1245371824, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430f4748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(430f4748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=516 entropy=510
D/wpa_supplicant( 1176): Add randomness: count=517 entropy=511
D/wpa_supplicant( 1176): Add randomness: count=518 entropy=512
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=519 entropy=513
D/wpa_supplicant( 1176): Add randomness: count=520 entropy=514
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkE,vent SupplicantStartedState
D/wpa_supplicant( 1176): Add randomness: count=521 entropy=515
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001263624637
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001263624663
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001263624674
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1263624637, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1263624663, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1263624674, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4315e170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423b36e8: PendingIntentRecord{427ea230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1270523, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4315e170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4305ede0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4305ede0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4529): Error opening trace file: No such file or directory (2)
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=522 entropy=516
D/wpa_supplicant( 1176): Add randomness: count=523 entropy=517
D/wpa_supplicant( 1176): Add randomness: count=524 entropy=518
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 9
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 0
I/wpa_supplicant( 1176): wpa_s->is_screen_on 0
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1176): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1176): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1176): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=525 entropy=519
D/wpa_supplicant( 1176): Add randomness: count=526 entropy=520
D/wpa_supplicant( 1176): Add randomness: count=527 entropy=521
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): clear disabled list - type=1
I/wpa_supplicant( 1176): No suitable network found
W/wpa_supplicant( 1176): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1176): State: INACTIVE -> INACTIVE
D/CustomizationManager( 4529): ====startRecUseTime====
D/htc.customization.log.level( 4529):  is 
W/CustomizationLogLevel( 4529): Level value is invalid, use default level 2
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (376) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000001281872908
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-56
I/wpa_supplicant( 1176): tsf=0000001281872929
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-72
I/wpa_supplicant( 1176): tsf=0000001281872939
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1281872908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1281872929, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1281872939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/CustomizationManager( 4529):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4529): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4529): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4529): Parsing tag category name = system
I/CustomizationCIDLoader( 4529): Parsing tag category name = application
I/CustomizationCIDLoader( 4529): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4529): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4529): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4529): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4529): Parsing tag category name = Settings
D/CustomizationManager( 4529):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4529):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 4529): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4529): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4529): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4529): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4529, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  909): Skipping PackageSetting{42a9ea08 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1887): Unregistering com.test.thalitest
E/acms    ( 1887): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(43213fe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1425 10028 null
D/PMS     (  909): releaseWL(43213fe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/PackageManager(  909): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  909): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Scheme: "sms"
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PackageBroadcastService( 2251): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4543 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Delaying start of: ServiceRecord{42f159d8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PeopleContactsSync( 2251): CP2 sync disabled
I/MultiDex( 4543): install
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2251, uid=10028, userID:0
I/MultiDex( 4543): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/MultiDex( 4543): loading existing secondary dex files
I/MultiDex( 4543): load found 1 secondary dex files
I/MultiDex( 4543): install done
F/PackageManager(  909): Unable to backup user packages state file, current changes will be lost at reboot
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1454949852528.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  909): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  909): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  909): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  909): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  909): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  909): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  909): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  909): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  909): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  909): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  909): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  909): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  909): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 18 more
D/PMS     (  909): acquireWL(42c86b08): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
I/Icing   ( 2251): doRemovePackageData com.test.thalitest
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.corpusid-1
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2251): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2251): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2251): Writing status failed
D/PMS     (  909): releaseWL(42c86b08): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4564 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4543): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 2251): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2251): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2251): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2251): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2251): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2251): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2251): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2251): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2251): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2251): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2251): Runtime exception while performing operation
E/ClearPendingStateOp( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2251): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2251): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2251): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2251): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2251): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2251): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2251): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2251): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2251): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2251): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2251): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2251): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2251): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2251): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2251): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2251): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2251): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2251): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2251): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4564): install
I/MultiDex( 4564): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/DropBoxManagerService(  909): Can't write: system_app_wtf
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/MultiDex( 4564): loading existing secondary dex files
I/MultiDex( 4564): load found 1 secondary dex files
I/MultiDex( 4564): install done
I/ProviderInstaller( 4564): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SharedPreferencesImpl( 1213): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/SQLiteLog( 1405): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1405): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9b5b60
W/[PluginManager]RegisterService( 1405): provider may killed!
W/[PluginManager]RegisterService( 1405): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1405): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1405): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1405): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1405): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1405): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1405): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4543): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4543): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4543): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4543): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4543): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4543): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4543): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4543): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4543): threadid=12: thread exiting with uncaught exception (group=0x41efbe30)
E/AndroidRuntime( 4543): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4543): Process: com.google.android.gms.drive, PID: 4543
E/AndroidRuntime( 4543): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4543): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4543): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4543): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4543): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4543): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4543): 	at ctn.run(SourceFile:985)
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
I/IcingCorporaProvider( 2926): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 4543): killProcess, pid=4543
D/Process ( 4543): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Recipient 4543
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4543) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4585 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2926): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2926): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63deccc8
W/dalvikvm( 2926): threadid=14: thread exiting with uncaught exception (group=0x41efbe30)
E/AndroidRuntime( 2926): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2926): Process: com.google.android.googlequicksearchbox:search, PID: 2926
E/AndroidRuntime( 2926): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2926): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2926): 	at cid.d(PG:186)
E/AndroidRuntime( 2926): 	at clo.g(PG:594)
E/AndroidRuntime( 2926): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2926): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2926): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2926): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2926): 	at clr.tL(PG:827)
E/AndroidRuntime( 2926): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2926): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2926): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2926): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2926): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2926): killProcess, pid=2926
D/Process ( 2926): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/ActivityManager(  909): Recipient 2926
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.googlequicksearchbox:search (pid 2926) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  909): Client com.google.android.googlequicksearchbox (pid 2926): Died!
D/WifiService(  909): Client connection lost with reason: 4
E/SQLiteDatabase( 2251): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2251): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2251): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2251): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2251): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2251): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2251): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2251): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2251): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2251): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2251): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2251): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2251): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2251): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2251): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2251): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2251): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2251): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2251): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2251): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2251): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2251): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2251): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2251): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2251): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2251): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2251): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2251): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2251): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2251): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2251): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2251): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2251): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2251): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2251): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2251): threadid=10: thread exiting with uncaught exception (group=0x41efbe30)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2251): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2251): Process: com.google.android.gms, PID: 2251
E/AndroidRuntime( 2251): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2251): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2251): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2251): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2251): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2251): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2251): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2251): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2251): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  909): killProcessQuiet, pid=2251
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  909): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  909): Killing 2251:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@423bee08 +
I/Prism.WidgetManager( 1271): onLoadItems() +
E/SQLiteDatabase( 4585): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4585): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4585): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4585): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4585): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4585): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4585): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4585): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4585): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4585): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4585): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4585): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4585): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4585): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4585): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4585): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4585): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4585): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4585): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4585): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4585): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4585): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4585): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4585): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4585): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4585): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4585): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4585): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4585): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4585): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4585): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4585): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4585): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4585): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQ,LiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4585): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4585): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4585): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4585): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4585): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4585): threadid=11: thread exiting with uncaught exception (group=0x41efbe30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4585): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4585): Process: com.google.android.apps.docs, PID: 4585
E/AndroidRuntime( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4585): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4585): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4585): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4585): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4585): 	at aho.run(AbstractDatabaseInstance.java:455)

```
