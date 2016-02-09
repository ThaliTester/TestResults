#### Test 583805003a0697c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
--------- beginning of /dev/log/system
V/AlarmManager(  911): sending alarm PendingIntent{42652888: PendingIntentRecord{424cc690 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71341, Int=0
E/cutils-trace( 4281): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4281): ====startRecUseTime====
D/htc.customization.log.level( 4281):  is 
W/CustomizationLogLevel( 4281): Level value is invalid, use default level 2
D/CustomizationManager( 4281):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4281): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4281): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4281): Parsing tag category name = system
I/CustomizationCIDLoader( 4281): Parsing tag category name = application
I/CustomizationCIDLoader( 4281): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4281): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4281): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4281): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4281): Parsing tag category name = Settings
D/CustomizationManager( 4281):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4281):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4281): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4281): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4281): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4281): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4281
I/GAV2    ( 4119): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  911): acquireWL(4232fb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4232fb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1510): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1510): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4295 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4142): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4142): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4142): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4142): Cust_ConnectToPC   : spcsc>false
D/        ( 4142): Cust_ConnectToPC   : IPT>true
,D/        ( 4142): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4142): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4142): Index of the first 1 = -1
,W/Settings( 4142): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4142): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4142): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4142): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4142): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  911): acquireWL(42625910): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3860 10154 null
,I/ActivityManager(  911): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3860): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3860): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/SensorManager(  911): mEventCount = 600
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3860, uid=10154, userID:0
,I/MusicLeanback( 3860): Conditions not met for autocaching.
,I/MusicLeanback( 3860): Stop autocaching.
D/PMS     (  911): releaseWL(42625910): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4315 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/Process (  911): killProcessQuiet, pid=3904
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3904:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3904
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 4315): Loading default preferences
,W/Resources( 4315): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  911): New client listening to asynchronous messages
,D/SyncApplication( 4315): Overriding preferences with custom values
,D/SyncApplication( 4315): Updating preferences succeeded
,E/SyncApplication( 4315): Application created.
D/VolumeInfo( 4315): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4315): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4315): Found 0 mount point(s)
,V/VolumeInfo( 4315): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4315): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4315): getNewCalendarAuthority()...
,D/VolumeInfo( 4315): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4315): Can not create volume ID for unmounted volume null
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4315, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4315, uid=10008, userID:0
,W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4315): enableAppOperation()+
D/SyncApplication( 4315): enableAppOperation()-
D/HTCUtilities( 4315): isNeorSinged() + 
,D/HTCUtilities( 4315): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4315): isNeorSinged() return false
,D/CDMountReceiver( 4315): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4315): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1614): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4315): enable CD Auto-mount: true
,D/HTCUtilities( 4315): enable auto-mount
,D/HTCUtilities( 4315): enable auto-mount
,I/ActivityManager(  911): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c62410 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 3 17 4 11
,I/RemoteViews( 1120): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c62830 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3843): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  911): killProcessQuiet, pid=3974
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Killing 3974:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  911): Recipient 3974
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  911): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/ConnectivityService(  911): getAllNetworkInfo called by  (2446/10021)
,D/PMS     (  911): acquireWL(425da578): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2446 10021 WorkSource{10016}
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  911): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/ConnectivityService(  911): getAllNetworkInfo called by  (2446/10021)
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4260a628 u0 com.htc.musicenhancer/.EnhancerService}
,I/AdsMeasurementBroadcastReceiver( 2250): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2250): Unauthorized to start the main service
D/PMS     (  911): acquireWL(42608bb0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2446 10021 WorkSource{10016}
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  911): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4343 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/DownloadManager( 2446): Download 289 starting
,D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=108 rxSum=105} preTxRxSum={txSum=68 rxSum=74}
,D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=20289 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  911): releaseWL(42652ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20290 delay=15s
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getAllNetworkInfo called by  (2446/10021)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2446/10021)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2446): Download 290 starting
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getAllNetworkInfo called by  (2446/10021)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=100 [1][1][0]
I/wpa_supplicant( 1169): Change stage from stage0 to stage3
I/wpa_supplicant( 1169): wlan0: Background scan every 600 seconds
,D/CalendarApplication( 4343): onCreate
D/ProviderChangeReceiver( 4343): ---------------------------------------------------
,D/ProviderChangeReceiver( 4343): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4343): start to updateAlertNotification!
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2446/10021)
,I/DownloadManager( 2446): Ignoring Content-Length since Transfer-Encoding is also defined
D/Process (  911): killProcessQuiet, pid=3962
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4360 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  911): Killing 3962:com.htc.updater/u0a84 (adj 15): empty #17
D/AlertService( 4343): No fired or scheduled alerts
D/HtcAlertUtils( 4343): -- cancelReminderNotification --
D/HtcAlertUtils( 4343): broadcastExistReminder!
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  911): Recipient 3962
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2446/10021)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,V/Settings:HtcSettingsApplication( 4360): [4360/4360] onCreate(),
W/ContextImpl( 4360): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/DownloadManager( 2446): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Process (  911): killProcessQuiet, pid=3581
,I/ActivityManager(  911): Killing 3581:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2446/10021)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=14 [21][3][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2446): Download 289 finished with status SUCCESS
D/PMS     (  911): releaseWL(425da578): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4164): Update downloaded, starting installation
,I/UpdateFetcherService( 4164): Started installation
D/WIFI_ICON( 1120): WifiActivity: 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/DownloadManager( 2446): Download 290 finished with status SUCCESS
D/PMS     (  911): releaseWL(42608bb0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3581
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4164): Update downloaded, starting installation
,I/UpdateFetcherService( 4164): Started installation
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [11][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 242
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/ConfigUpdateInstallReceiver(  911): Not installing, new version is <= current version
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 9 times.
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/PackageSettings(  911): Skipping PackageSetting{422487f8 com.test.thalitest/10189} due to missing metadata
,D/PMS     (  911): releaseWL(42539248): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 268
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:201, mTXpacketCount:137, avgLinkspeed:53,mAvgTxRate72
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 10 times.
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 26
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/PMS     (  911): acquireWL(42615d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10073}
,V/AlarmManager(  911): sending alarm PendingIntent{42389e78: PendingIntentRecord{424c3210 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455056146147, Int=0
,D/PMS     (  911): releaseWL(42615d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4083): [1] 5.onFinished: Installation state replication succeeded.
,I/SensorManager(  911): mEventCount = 750
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 52
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/AutoSetting( 1390): service - has update message, not stop
,D/AutoSetting( 1390): service - mHandler: update timezone
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1614): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1614): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c93f00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 7 2 11
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 11 times.
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 124
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97,
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  911):    returned true,
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=153 rxSum=147} preTxRxSum={txSum=108 rxSum=105}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=20290 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20291 delay=15s
D/PMS     (  911): acquireWL(425af9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{4263c6e0: PendingIntentRecord{424cc690 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88855, Int=0
D/PMS     (  911): releaseWL(425af9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1169): Change stage from stage3 to stage0
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 196
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 12 times.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 268
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true,
D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:202, mTXpacketCount:201, avgLinkspeed:53,mAvgTxRate72,
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1510): handler message = 4011
,E/HtcModeClient( 1510): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1510): Don't start project servcice
,D/HtcModeClient( 1510): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1510): connectState: CONNECTION_READY = false
D/SilentMusic( 1510): call stop
,D/HtcModeClient( 1510): close connection
,W/HtcModeClient( 1510): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1510): read the terminate packet, so break
,D/PMS     (  911): acquireWL(426dd440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=94931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426dd440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1120): now=1455056160034 next=59966
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{425e8800 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  911): acquireWL(428113e8): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(428113e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  911): acquireWL(4264fa40): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(4264fa40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  911): acquireWL(42814ed0): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(42814ed0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  911): acquireWL(426c6140): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(426c6140): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=148} preTxRxSum={txSum=153 rxSum=147}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=20291 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20292 delay=15s
D/PMS     (  911): acquireWL(4280eca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{42669700: PendingIntentRecord{424cc690 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103860, Int=0
D/PMS     (  911): releaseWL(4280eca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  911): acquireWL(4271ff20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10028}
,V/AlarmManager(  911): sending alarm PendingIntent{42641990: PendingIntentRecord{4258bb20 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455056153582, Int=563223000
,D/PMS     (  911): acquireWL(427f5530): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2250 10028 null
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4392 uid=10077 gids={50077}
,V/AlarmManager(  911): sending alarm PendingIntent{4264c460: PendingIntentRecord{426569b0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455056169508, Int=60000
,D/PMS     (  911): releaseWL(4271ff20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  911): acquireWL(427f7a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(427f5530): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,I/CheckinService( 2250): Preparing to send checkin request
,I/EventLogService( 2250): Accumulating logs since 1455056118967
,W/EventLogAggregator( 2250): Unknown tag: install_package_attempt
,W/EventLogAggregator( 2250): Unknown tag: snet
,W/EventLogAggregator( 2250): Unknown tag: snet_gcore
,D/SMSBackup( 4392): SMSBackupAgentService started
,D/SMSBackup( 4392): Checking restore status
,D/SMSBackup( 4392): Restore complete
,D/SMSBackup( 4392): cancelCheckAlarm
,D/SMSBackup( 4392): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  911): killProcessQuiet, pid=2775
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2775:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2775
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
,I/GoogleHttpClient( 2250): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2250): Using GMS GoogleHttpClient
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1614): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1614): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41d97d60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 9 3 12
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4406 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4406): install
,I/MultiDex( 4406): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4406): loading existing secondary dex files
,I/MultiDex( 4406): load found 1 secondary dex files
,I/MultiDex( 4406): install done
,I/ProviderInstaller( 4406): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Adreno-EGL( 4406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4406): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4406): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4406): Local Branch: 
I/Adreno-EGL( 4406): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4406): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4406):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4406): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4406): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4406): Local Branch: 
I/Adreno-EGL( 4406): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4406): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4406):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4406): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4406): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4406): Local Branch: 
I/Adreno-EGL( 4406): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4406): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4406):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4406/10028)
,W/Settings( 4406): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 2250): Sending checkin request (9013 bytes)
D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2250): [NET] getaddrinfo-,err=8
D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2250): [NET] getaddrinfo-, 1
,D/libc    ( 2250): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f38c +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2250): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  911): acquireWL(426a4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  911): releaseWL(426a4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [13][0][0]
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1614): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1614): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e11228 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 7 3 12
,I/CheckinTask( 2250): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2250): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  911): releaseWL(427f7a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2250): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c4a250 that was originally bound here
E/ActivityThread( 2250): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c4a250 that was originally bound here
E/ActivityThread( 2250): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2250): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2250): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2250): 	,at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2250): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2250): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2250): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2250): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2250): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2250): 	at bks.a(SourceFile:298)
E/ActivityThread( 2250): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2250): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2250): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1364): GCM config loaded
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:217, mTXpacketCount:202, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/Process (  911): killProcessQuiet, pid=4037
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4037:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4037
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4217db18
,W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  911): mWirelessDisplayManager is null
W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/SensorService(  911): pid=911, uid=1000
,W/SensorService(  911): Active sensors: size = 2
,W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4217db18, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231ab40
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@41cd5b90
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 368ms
,W/PnPMgr  (  350): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
D/PMS     (  911): OOBE c monitor 11
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=1273
,D/PMS     (  911): acquireWL(4286fe78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/NfcService( 1258): applyRouting -2
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427059e0)
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
D/PMS     (  911): acquireWL(4286c738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  911): wakingUp
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(4286c738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  911): No lock screen! windowToken=null
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMN     (  911): onScreenOn
D/PMS     (  911): releaseWL(4286fe78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  911): updateBatteryInfo
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/MtpService( 2446): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2446): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
D/NfcService( 1258): applyRouting -2
,D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): acquireWL(4284fe60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20293 delay=15s
D/PMS     (  911): releaseWL(4284fe60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/ContextImpl( 4295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ClockThread( 1120): stop update clock
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:On
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4295): isEpsOn(), nState = 0
,V/SRS_Proc(  370): ParamSet string: screen_state=on
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  911): acquireWL(42824618): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4295 1000 null
,D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  911): updateScreenOn: false
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  911): releaseWL(42824618): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1390): receiver - intent: android.intent.action.USER_PRESENT
,D/SmartSyncUtils( 4295): getMobilePolicyEnabled, result = true
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1390): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 4142): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4142): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4142): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4142): Cust_ConnectToPC   : spcsc>false
D/        ( 4142): Cust_ConnectToPC   : IPT>true
D/        ( 4142): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4142): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4142): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4142): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4142): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4142): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4142): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4142): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4142):  defaultType:0
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1861): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1861): onScreenOn: 1455056177178
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1861): onScreenOn: 1455056177179
D/PMS     (  911): acquireWL(427d71c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
D/PMS     (  911): releaseWL(427d71c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231ab40
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4231ab40, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@41cd5b90
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
,D/PMS     (  911): acquireWL(427d6a40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c428b0
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
,I/AlarmManager(  911): [AlarmQueuing] data connection: true
,I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20293 mDataStallAlarmIntent=PendingIntent{42625bb8: PendingIntentRecord{424cc690 android broadcastIntent}}
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:Off
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(42548fa0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(427d6a40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
W/ContextImpl( 4295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4295): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4295): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4295): isEpsOn(), nState = 0
D/NetworkPolicy(  911): updateScreenOn: false
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cd5b90
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cd5b90, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cd5b90, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cd5b90
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41face90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41face90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  911): releaseWL(42548fa0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/AutoSetting( 1390): service - mHandler: cancel location update
,D/AutoSetting( 1390): service -           changes count: 0
,D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1614): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1861): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1861): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1861): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1861): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1861): onScreenOff
D/PMS     (  911): acquireWL(41dc6498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
D/PMS     (  911): releaseWL(41dc6498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4218
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4218:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4218
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=3885
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3885:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3885
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(41b937d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PMS     (  911): releaseWL(41b937d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(427e7d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42323760: PendingIntentRecord{42009928 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141874, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{41f29638: PendingIntentRecord{424ded90 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142241, Int=0
,D/AutoSetting( 1390): service - handleMessage() stop self
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(427e8c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
,D/AutoSetting( 1390): service - handleMessage() quit looper
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  911): releaseWL(427e7d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  911): acquireWL(427ed838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/AutoSetting( 1390): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=4241
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7d3d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/ActivityManager(  911): Killing 4241:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/PMS     (  911): releaseWL(427ed838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  911): Recipient 4241
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  911): acquireWL(41cd2128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(41cd2128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): releaseWL(427e8c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(42339750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42339750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/PMS     (  911): acquireWL(42591be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10026}
,V/AlarmManager(  911): sending alarm PendingIntent{423300e0: PendingIntentRecord{422c2b38 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174269, Int=0
,D/PMS     (  911): releaseWL(42591be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(4264d038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4264d038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(423b8e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  911): releaseWL(423b8e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(42337ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42337ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  911): acquireWL(425ffec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425ffec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(423c7508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(423c7508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(426e6a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  911): releaseWL(426e6a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1614): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1614): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,W/AppWidgetServiceImpl(  911): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(425e3338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=334930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425e3338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  911): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4451 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  911): acquireWL(4256be38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10047}
,V/AlarmManager(  911): sending alarm PendingIntent{41b41650: PendingIntentRecord{42624570 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455056286108, Int=10800000
,V/AlarmManager(  911): sending alarm PendingIntent{41fe1fd8: PendingIntentRecord{42561d50 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1455056421537, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42526720: PendingIntentRecord{41e48c80 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455056426770, Int=1800000
,D/PMS     (  911): acquireWL(4256de30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2250 10028 null
,D/PMS     (  911): releaseWL(4256be38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  911): acquireWL(424b7820): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2250 10028 null
,I/EventLogService( 2250): Aggregate from 1455056169577 (log), 1455054626705 (data)
D/PMS     (  911): releaseWL(4256de30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.aurora (4451/10047)
,D/Process (  911): killProcessQuiet, pid=4119
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Uploader( 2250): No account for auth token provided
D/PMS     (  911): releaseWL(424b7820): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
I/ActivityManager(  911): Killing 4119:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2250): [NET] getaddrinfo-,err=8
D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2250): [NET] getaddrinfo-, 1
,D/libc    ( 2250): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1d84 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 289,
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS,
D/libc    ( 2250): [NET] getaddrinfo_proxy-, success
I/global  ( 2250): call createSocket() return a new socket.
D/libc    ( 2250): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-, SUCCESS,
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4119
,D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1614): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1614): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,E/PlayEventLogger( 4083): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4083): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4083): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4083): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4083): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4083): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4083): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4083): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c31f80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 2 11 3 12
,D/libc    ( 4083): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4083): [NET] getaddrinfo-,err=8
D/libc    ( 4083): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4083): [NET] getaddrinfo-, 1
,D/libc    ( 4083): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =476d +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4083): [NET] getaddrinfo_proxy-, success
I/global  ( 4083): call createSocket() return a new socket.
,D/libc    ( 4083): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4083): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4083): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4083): [NET] getaddrinfo-,err=8
,D/PMS     (  911): acquireWL(426bdb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426bdb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(426d9ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426d9ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4263fcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4263fcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(426ba990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=454931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426ba990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(426b4998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426b4998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(42573930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=514931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42573930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(42617900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42617900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  911): acquireWL(425ca370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=574931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(425ca370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(423a9cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(423a9cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  911): acquireWL(426b5f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=634931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426b5f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  911): killProcessQuiet, pid=3627
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3627:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3627
,D/PMS     (  911): acquireWL(426b16d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426b16d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1169): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1169): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1169): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1169): Add randomness: count=11 e,ntropy=5
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000676275002
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000676274978
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-77
I/wpa_supplicant( 1169): tsf=0000000676275015
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@425dc060 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@425dc060 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@425dc060 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 676275002, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 676274978, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 676275015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter,
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-44
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1169): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1169): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1169): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-44
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 la,st_scan_full=0
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1169): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1169): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1169): Add randomness: count=19 entropy=13
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000693691675
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-44
I/wpa_supplicant( 1169): tsf=0000000693691635
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000693691685
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
,I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000693691660
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 693691675, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -44, frequency: 5220, timestamp: 693691635, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 693691685, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 693691660, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-44], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(426da5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000},
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=694930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426da5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1169): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1169): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1169): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1169): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1169): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1169): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000711075584
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000711075546
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000711075594
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000711075573
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 711075584, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 711075546, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 711075594, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 711075573, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1,
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==,
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1169): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1169): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1169): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1169): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1169): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1169): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1,
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000728481469
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000728481431
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000728481479
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000728481458
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 728481469, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 728481431, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 728481479, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 728481458, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults,
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4264fde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4264fde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1169): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1169): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1169): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1169): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1169): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1169): Add randomness: count=43 entropy=37
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000745864896
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000745864859
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000745864906
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000745864885
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0,
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 745864896, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 745864859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 745864906, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 745864885, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(426ec938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=754930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(426ec938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1169): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1169): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1169): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1169): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1169): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1169): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1,
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000763275166
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000763275129
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000000763275176
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000763275155
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 763275166, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 763275129, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 763275176, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 763275155, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1169): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1169): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1169): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1169): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1169): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1169): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  911): getDiscoveryDongleList
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000780711045
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000780711008
,I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000000780711054
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000780711034
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 780711045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 780711008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 780711054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 780711034, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4280a420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4280a420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1169): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1169): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1169): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1169): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1169): Add randomness: count=66 entropy=60
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1169): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1169): Add randomness: count=69 entropy=63
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (631) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000798125346
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000798125308
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000798125355
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000798125334
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-88
I/wpa_supplicant( 1169): tsf=0000000798125364
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC0039325
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 798125346, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 798125308, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 798125355, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 798125334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 798125364, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter,
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  911): acquireWL(4262c8c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=814930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4262c8c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1169): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1169): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1169): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1169): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1169): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1169): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1169): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1169): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (631) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000815541353
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000815541316
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000815541363
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000815541342
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-88
I/wpa_supplicant( 1169): tsf=0000000815541371
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC0039325
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 815541353, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 815541316, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 815541363, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 815541342, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 815541371, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1169): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1169): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1169): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1169): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1169): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1169): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1169): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1169): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1169): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (631) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000832955834
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000832955798
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-77
I/wpa_supplicant( 1169): tsf=0000000832955844
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000832955824
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-88
I/wpa_supplicant( 1169): tsf=0000000832955853
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC0039325
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 832955834, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 832955798, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 832955844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 832955824, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0,
D/WifiStateMachine(  911): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 832955853, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1169): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1169): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1169): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1169): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (631) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
,I/wpa_supplicant( 1169): tsf=0000000850082702
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000832955798
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000000850082714
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
,I/wpa_supplicant( 1169): tsf=0000000832955824
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-88
I/wpa_supplicant( 1169): tsf=0000000832955853
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC0039325
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 850082702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 832955798, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 850082714, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 832955824, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 832955853, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 5 to mScanResults,
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000),
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/PMS     (  911): acquireWL(428c5d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(428c5d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1169): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1169): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1169): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1169): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1169): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1169): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000867514711
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000867514673
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-77
I/wpa_supplicant( 1169): tsf=0000000867514722
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-49
I/wpa_supplicant( 1169): tsf=0000000867514699
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 867514711, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 867514673, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 867514722, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 867514699, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-49], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(428deb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=874930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(428deb90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1169): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1169): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1169): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1169): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1169): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1169): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000884925284
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000884925246
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-77
I/wpa_supplicant( 1169): tsf=0000000884925296
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-49
I/wpa_supplicant( 1169): tsf=0000000884925273
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 884925284, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 884925246, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 884925296, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 884925273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-49], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1169): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1169): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1169): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1169): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1169): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1169): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000902352114
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000902352075
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000902352124
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-49
I/wpa_supplicant( 1169): tsf=0000000902352102
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wp,a_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 902352114, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 902352075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 902352124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 902352102, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-49], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4290f868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4290f868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1169): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1169): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50,
D/wpa_supplicant( 1169): Sorted scan results
,I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1169): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1169): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000919765112
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000902352075
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-77
I/wpa_supplicant( 1169): tsf=0000000919765124
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-49
I/wpa_supplicant( 1169): tsf=0000000902352102
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified ,user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 919765112, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 902352075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 919765124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 902352102, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-49], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1,
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  911): acquireWL(42928698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=934931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42928698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1169): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1169): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1169): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1169): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000937179276
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-45
I/wpa_supplicant( 1169): tsf=0000000937179250
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000000937179287
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 937179276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 937179250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 937179287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1169): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1169): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
,I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1,
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
,I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1169): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1169): Add randomness: count=137 entropy=131
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
,W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000954585314
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-45
I/wpa_supplicant( 1169): tsf=0000000954585288,
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000000954585325
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 954585314, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 954585288, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 954585325, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1169): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1169): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1169): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1169): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000972011372
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000972011343
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
,I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000972011383
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 972011372, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 972011343, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 972011383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42822650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42822650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1169): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1169): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1169): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1169): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000989414797
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000989414771
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000000989414808
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
,I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 989414797, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 989414771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 989414808, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/PMS     (  911): acquireWL(423a8440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(423a8440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1169): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1169): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
,I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=153 entropy=147
,D/wpa_supplicant( 1169): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1169): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  911): getDiscoveryDongleList
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001006815035
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-45
I/wpa_supplicant( 1169): tsf=0000001006815008
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-73
I/wpa_supplicant( 1169): tsf=0000001006815045
,I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1006815035, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1006815008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1006815045, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 3 to mScanResults
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4205ce90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41df0e78: PendingIntentRecord{42419f18 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784409, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{41fed670: PendingIntentRecord{4241f750 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=929116, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{42508e88: PendingIntentRecord{424ddd38 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455057006773, Int=900000
D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  911): sending alarm PendingIntent{421fad60: PendingIntentRecord{423f4c70 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455057077226, Int=0
,D/ConnectivityService(  911): Done.
,D/ConnectivityService(  911): Setting timer for 720seconds
,D/PMS     (  911): acquireWL(425822e8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  911): releaseWL(425822e8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  911): acquireWL(425806c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  911): releaseWL(425806c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4295): call getInstance()
,D/SmartSyncUtils( 4295): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4295): MY_DEBUG = false
D/PMS     (  911): releaseWL(4205ce90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): acquireWL(42330058): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4295 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4295): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4295): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4295): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4295): SettingOnTime = 1455084000000, randomSettingOnTime = 1455080491000
,D/SmartSyncScreenOnOffTimeReceiver( 4295): SettingOffTime = 1455062400000, randomSettingOffTime = 1455068373000
,D/SmartSyncScreenOnOffTimeReceiver( 4295): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4295): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4295): bNightModeTurnOffOnce = false
D/PMS     (  911): acquireWL(41f423b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/PMS     (  911): releaseWL(42330058): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  911): releaseWL(41f423b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  911): acquireWL(4231d168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  911): releaseWL(4231d168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-68
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1169): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1169): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
,I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-68
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1169): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1169): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001024235096
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-45
I/wpa_supplicant( 1169): tsf=0000001024235069
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
,I/wpa_supplicant( 1169): level=-68
I/wpa_supplicant( 1169): tsf=0000001024235107
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1024235096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1024235069, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -68, frequency: 2412, timestamp: 1024235107, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 3 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 13 [-68], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4279bd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4279bd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1169): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1169): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1169): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1169): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1169): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1169): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001041645434
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001041645396
,I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-76
I/wpa_supplicant( 1169): tsf=0000001041645444
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001041645422
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1041645434, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1041645396, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1041645444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1041645422, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==,
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42423880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42423880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1169): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1169): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1169): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1169): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1169): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1169): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001058752363
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
,I/wpa_supplicant( 1169): tsf=0000001058752325
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000001058752373
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====,
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001058752352
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0,
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1058752363, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1058752325, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1058752373, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1058752352, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1169): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1169): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1169): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1169): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1169): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1169): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001076192476
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001076192439
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====,
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000001058752373
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001076192465
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1076192476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1076192439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1058752373, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1076192465, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter,
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  911): acquireWL(4253d9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4253d9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1169): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1169): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1169): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1169): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1169): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1169): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001093575107
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001093575069
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-75
I/wpa_supplicant( 1169): tsf=0000001058752373
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7,
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001093575096
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1093575107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1093575069, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1058752373, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1093575096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1169): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1169): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1169): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1169): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001110992188
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001110992162
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-74
I/wpa_supplicant( 1169): tsf=0000001110992199
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001093575096
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1110992188, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1110992162, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1110992199, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1093575096, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults,
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(427e7f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1114930, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(427e7f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1169): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1169): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
,I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=203 entropy=197
,D/wpa_supplicant( 1169): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1169): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001128374954
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001128374928
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-74
I/wpa_supplicant( 1169): tsf=0000001128374965
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1128374954, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1128374928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1128374965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1169): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1169): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1169): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1169): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001145787788
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001145787762
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-74
I/wpa_supplicant( 1169): tsf=0000001145787799
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1145787788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1145787762, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1145787799, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 3 to mScanResults,
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4271f0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4271f0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1169): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1169): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1169): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1169): Add randomness: count=217 entropy=211
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-,wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001163178095
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001163178069
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-74
I/wpa_supplicant( 1169): tsf=0000001163178105
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1163178095, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1163178069, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1163178105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4281cf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1174931, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(4281cf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available,
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46,
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1169): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1169): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48,
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0,
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1169): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1169): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1169): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
,I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001180605037
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001180605011
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-78
I/wpa_supplicant( 1169): tsf=0000001180605048
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  911): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1180605037, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1180605011, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1180605048, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 3 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (3) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter,
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1169): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1169): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1169): Add randomness: count=227 entropy=221
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1169): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1169): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1169): Add randomness: count=231 entropy=225
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001198000695
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000001198000657
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-78
I/wpa_supplicant( 1169): tsf=0000001198000706
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-54
I/wpa_supplicant( 1169): tsf=0000001198000684
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1198000695, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1198000657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1198000706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1198000684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(428d30d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(428d30d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1169): Add randomness: count=233 entropy=227
D/wpa_supplicant( 1169): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1169): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=236 entropy=230
D/wpa_supplicant( 1169): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1169): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1169): Add randomness: count=239 entropy=233
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001215392292
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000001215392255
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-74
I/wpa_supplicant( 1169): tsf=0000001215392302
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-53
I/wpa_supplicant( 1169): tsf=0000001215392281
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1215392292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1215392255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1215392302, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 1215392281, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available,
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=240 entropy=234,
D/wpa_supplicant( 1169): Add randomness: count=241 entropy=235
D/wpa_supplicant( 1169): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1169): Add randomness: count=243 entropy=237
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
,I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
,I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
,W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
,D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1169): Add randomness: count=245 entropy=239
D/wpa_supplicant( 1169): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1169): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001232772439
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000001232772401
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-73
I/wpa_supplicant( 1169): tsf=0000001232772449
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-55
I/wpa_supplicant( 1169): tsf=0000001232772428
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1232772439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1232772401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1232772449, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1232772428, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4288f5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
V/AlarmManager(  911): sending alarm PendingIntent{42057570: PendingIntentRecord{41cfc1d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1234930, Int=0
,D/PMS     (  911): releaseWL(4288f5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=248 entropy=242
D/wpa_supplicant( 1169): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1169): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1169): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1169): Add randomness: count=253 entropy=247
D/wpa_supplicant( 1169): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1169): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
,D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (489) for get BSS: id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001250102461
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000001250102423
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
,I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-73
I/wpa_supplicant( 1169): tsf=0000001250102472
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001250102449
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1250102461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1250102423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1250102472, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1250102449, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1169): Add randomness: count=257 entropy=251
D/wpa_supplicant( 1169): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1169): Add randomness: count=259 entropy=253
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -48
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1169): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1169): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1169): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1169): Add randomness: count=263 entropy=257
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=1,
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000001267422197
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000001267422157
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====,
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-73
I/wpa_supplicant( 1169): tsf=0000001267422207
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000001267422184
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS],
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList,
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 1267422197, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1267422157, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 1267422207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 1267422184, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -48, 0
D/WifiStateMachine(  911): add 4 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-48], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-52], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42938800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42938800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
E/cutils-trace( 4476): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4476): ====startRecUseTime====
D/htc.customization.log.level( 4476):  is 
W/CustomizationLogLevel( 4476): Level value is invalid, use default level 2
D/CustomizationManager( 4476):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4476): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4476): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4476): Parsing tag category name = system
I/CustomizationCIDLoader( 4476): Parsing tag category name = application
I/CustomizationCIDLoader( 4476): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4476): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4476): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4476): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4476): Parsing tag category name = Settings
D/CustomizationManager( 4476):  Read CID file spent 0.177 (s)
D/CustomizationManager( 4476):  All configurations done spent 0.177 (s)
W/HtcNativeFlag( 4476): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4476): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4476): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4476): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4476, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  911): Skipping PackageSetting{422487f8 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  911): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  911): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  911): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1614): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1614): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1614): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1928): Unregistering com.test.thalitest
E/acms    ( 1928): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
D/PMS     (  911): acquireWL(429291d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
W/GeofencerStateMachine( 1426): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): releaseWL(429291d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1286): Cleaning up data for package: com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
D/PackageBroadcastService( 2250): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  911): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4490 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4490): install
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4490): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4490): loading existing secondary dex files
I/MultiDex( 4490): load found 1 secondary dex files
I/MultiDex( 4490): install done
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  911): Delaying start of: ServiceRecord{426e4268 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 2250): CP2 sync disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2250, uid=10028, userID:0
I/ProviderInstaller( 4490): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 2250): doRemovePackageData com.test.thalitest
D/PMS     (  911): acquireWL(42671aa8): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
I/ActivityManager(  911): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
D/PMS     (  911): releaseWL(42671aa8): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/SQLiteDatabase( 2250): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2250): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2250): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2250): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2250): Runtime exception while performing operation
E/ClearPendingStateOp( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2250): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2250): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2250): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2250): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2250): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2250): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2250): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  911): Can't write: system_app_wtf
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/ActivityManager(  911): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4513 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/SQLiteDatabase( 4490): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
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
E/SQLiteDatabase( 4490): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4490): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4490): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4490): threadid=12: thread exiting with uncaught exception (group=0x416ace30)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4490): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4490): Process: com.google.android.gms.drive, PID: 4490
E/AndroidRuntime( 4490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4490): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4490): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4490): 	at ctn.run(SourceFile:985)
D/Process ( 4490): killProcess, pid=4490
D/Process ( 4490): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/MultiDex( 4513): install
I/MultiDex( 4513): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4513): loading existing secondary dex files
I/MultiDex( 4513): load found 1 secondary dex files
I/MultiDex( 4513): install done
I/ProviderInstaller( 4513): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  911): Resuming delayed broadcast
E/SharedPreferencesImpl( 1212): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1390): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1390): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1390): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9e2838
W/[PluginManager]RegisterService( 1390): provider may killed!
W/[PluginManager]RegisterService( 1390): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1390): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1390): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1390): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1390): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1390): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1390): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1390): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1390): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1390): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2915): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  911): Recipient 4490
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.gms.drive (pid 4490) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4532 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
W/PackageManager(  911): Unable to load service info ResolveInfo{428a0408 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 2915): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2915): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x647c6498
W/dalvikvm( 2915): threadid=14: thread exiting with uncaught exception (group=0x416ace30)
E/ActivityManager(  911): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2915): killProcess, pid=2915
D/Process ( 2915): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2915): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2915): Process: com.google.android.googlequicksearchbox:search, PID: 2915
E/AndroidRuntime( 2915): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2915): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2915): 	at cid.d(PG:186)
E/AndroidRuntime( 2915): 	at clo.g(PG:594)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2915): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2915): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2915): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2915): 	at clr.tL(PG:827)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2915): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2915): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2915): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
E/SQLiteDatabase( 2250): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2250): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2250): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2250): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2250): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2250): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2250): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2250): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2250): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2250): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2250): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2250): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2250): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2250): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2250): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2250): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2250): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2250): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2250): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2250): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2250): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2250): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2250): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2250): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2250): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2250): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2250): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2250): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2250): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2250): threadid=10: thread exiting with uncaught exception (group=0x416ace30)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
D/Process (  911): killProcessQuiet, pid=2250
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
E/AndroidRuntime( 2250): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2250): Process: com.google.android.gms, PID: 2250
E/AndroidRuntime( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2250): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2250): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2250): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2250): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2250): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2250): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2250): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  911): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  911): Killing 2250:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  911): Client com.google.android.googlequicksearchbox (pid 2915): Died!
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Recipient 2915
I/ActivityManager(  911): Process com.google.android.googlequicksearchbox:search (pid 2915) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
D/WifiService(  911): Client connection lost with reason: 4
W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4532): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4532): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4532): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4532): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4532): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4532): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4532): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4532): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4532): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4532): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4532): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4532): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4532): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4532): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4532): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4532): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4532): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4532): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4532): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4532): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4532): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4532): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4532): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4532): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4532): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4532): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4532): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4532): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4532): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4532): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4532): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4532): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4532): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4532): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4532): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4532): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4532): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4532): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4532): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4532): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4532): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4532): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4532): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4532): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4532): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4532): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4532): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4532): threadid=11: thread exiting with uncaught exception (group=0x416ace30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4532): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4532): Process: com.google.android.apps.docs, PID: 4532
E/AndroidRuntime( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4532): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4532): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4532): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4532): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4532): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 4532): killProcess, pid=4532
D/Process ( 4532): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4550 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  911): Recipient 4532
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  911): killProcessQuiet, pid=3860
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3860:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4532) has died.
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3860
D/MediaRouterService(  911): Client com.google.android.music (pid 3860): Died!
W/ContextImpl( 4550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4563 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4550): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4550): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4550): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4550): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4550): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4550): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4550): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4550): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4550): threadid=10: thread exiting with uncaught exception (group=0x416ace30)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4550): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4550): Process: com.android.keychain, PID: 4550
E/AndroidRuntime( 4550): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4550): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4550): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4550): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4550): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4550): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4550): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4550): killProcess, pid=4550
D/Process ( 4550): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455057349439.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
I/ActivityManager(  911): Recipient 4550
I/ActivityManager(  911): Process com.android.keychain (pid 4550) has died.

```
