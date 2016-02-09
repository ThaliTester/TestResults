#### Test 5841644866d9c0e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  909): acquireWL(4258ff28): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
D/PMS     (  909): releaseWL(4258ff28): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  909): acquireWL(4256d580): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
D/PMS     (  909): releaseWL(4256d580): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
,I/ContactLoggerTask( 2911): canRun() : Disabled
I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 600 ms] updated apps [took 538 ms] updated contacts [took 62 ms]
D/Finsky  ( 4068): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4112 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/GAV2    ( 3978): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  909): acquireWL(42439600): PARTIAL_WAKE_LOCK  AsyncService 0x1 4112 10160 null
D/PMS     (  909): acquireWL(421dd4a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4112 10160 null
D/PMS     (  909): releaseWL(42439600): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  909): acquireWL(4254a198): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4112 10160 null
D/PMS     (  909): releaseWL(421dd4a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4112/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4112/10160)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(4254a198): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
D/Process (  909): killProcessQuiet, pid=3755
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  909): Killing 3755:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/GCM     ( 1370): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(4256ec88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3602 10070 null
D/PMS     (  909): acquireWL(4238f880): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3602 10070 null
D/PMS     (  909): acquireWL(424a9668): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3602 10070 null
D/PMS     (  909): releaseWL(4256ec88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  909): Delay finish: com.htc.task/.notification.NotifyReceiver
I/ActivityManager(  909): Recipient 3755
E/TodoTaskNotifyService( 3602): java.lang.NullPointerException
W/System.err( 3602): java.lang.NullPointerException
W/System.err( 3602): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3602): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3602): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3602): stopSelfResult false
E/TodoTaskNotifyService( 3602): java.lang.NullPointerException
W/System.err( 3602): java.lang.NullPointerException
W/System.err( 3602): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3602): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
D/PMS     (  909): acquireWL(4238f880): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3602 10070 null
D/PMS     (  909): releaseWL(424a9668): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  909): releaseWL(4238f880): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 3602): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/NotifyReceiver( 3602): mStartingService is null
W/NotifyReceiver( 3602): stopSelfResult true
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(426c4028): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3602 10070 null
E/TodoTaskNotifyService( 3602): java.lang.NullPointerException
W/System.err( 3602): java.lang.NullPointerException
W/System.err( 3602): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3602): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3602): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  909): acquireWL(425f52c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3602 10070 null
I/ActivityManager(  909): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  909): releaseWL(426c4028): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/NotifyReceiver( 3602): stopSelfResult true
D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  909): releaseWL(425f52c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(42590df0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42493be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/cutils-trace( 4107): Error opening trace file: No such file or directory (2)
D/PMS     (  909): releaseWL(42590df0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  909): releaseWL(42493be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/GCM     ( 1370): GCM config loaded
I/WSP     ( 1407): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1407): Weather sync is On
V/AlarmManager(  909): sending alarm PendingIntent{42501328: PendingIntentRecord{42618478 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455019775359, Int=0
I/WSP     ( 1407): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 09 14:09:35 CET 2016
D/Settings:HtcWirelessFeatureFlags( 3779): id/is att sku: 99/false
I/ActivityManager(  909): Delay finish: com.google.android.gm/.MailIntentReceiver
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
W/SystemReader( 3779): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/PMS     (  909): acquireWL(42792720): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1407 10053 null
W/SystemReader( 3779): Cannot find support_harman, use default value instead
W/SystemReader( 3779): Cannot find effect_manager_id, use default value instead
E/Settings:HtcWrapHeaderInfo( 3779): no such activity!
W/GLSUser ( 1370): GoogleAccountDataService.getToken()
D/TodoTaskshortcut( 3602): update TASK shortcut>
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3779): The wrap header doesn't exist in header list.
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/Settings:HtcWrapHeaderInfo( 3779): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3779): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]support         :false
D/CustomizationManager( 4107): ====startRecUseTime====
D/htc.customization.log.level( 4107):  is 
W/CustomizationLogLevel( 4107): Level value is invalid, use default level 2
W/FingerprintManager( 3779): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 3779): isSupportVoWifi: null
W/GLSUser ( 1370): GoogleAccountDataService.getToken()
E/ActivityThread( 3779): Failed to find provider info for com.htc.vowifi
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Finsky  ( 4068): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 4068): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3779): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3779): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3779): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3779): [supportHomeButton]support         :false
W/FingerprintManager( 3779): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 3779): isSupportVoWifi: null
D/CustomizationManager( 4107):  Read ACC file spent 0.069 (s)
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3779): Failed to find provider info for com.htc.vowifi
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4107): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4107): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4107): Parsing tag category name = system
I/CustomizationCIDLoader( 4107): Parsing tag category name = application
I/CustomizationCIDLoader( 4107): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4107): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4107): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4107): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4107): Parsing tag category name = Settings
D/CustomizationManager( 4107):  Read CID file spent 0.117 (s)
D/CustomizationManager( 4107):  All configurations done spent 0.117 (s)
W/HtcNativeFlag( 4107): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4107): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4107): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4107): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4107
I/GAV4    ( 4022): Thread[GAThread,5,main]: No campaign data found.
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Finsky  ( 4068): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 4068): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4068): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/Process (  909): killProcessQuiet, pid=3812
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3812:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  909): Recipient 3812
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  909): sending alarm PendingIntent{42611ef8: PendingIntentRecord{4258cdb0 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455019776476, Int=0
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 8 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/SensorManager(  909): mEventCount = 750
,D/PMS     (  909): acquireWL(426c1488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(426c1488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1520): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1520): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(42786c40): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3847 10154 null
,I/ActivityManager(  909): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3847): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3847): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3847, uid=10154, userID:0
,I/MusicLeanback( 3847): Conditions not met for autocaching.
,I/MusicLeanback( 3847): Stop autocaching.
D/PMS     (  909): releaseWL(42786c40): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3829): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4181 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4181): Loading default preferences
,W/Resources( 4181): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  909): New client listening to asynchronous messages
,D/SyncApplication( 4181): Overriding preferences with custom values
,D/SyncApplication( 4181): Updating preferences succeeded
,E/SyncApplication( 4181): Application created.
D/VolumeInfo( 4181): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4181): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4181): Found 0 mount point(s)
,V/VolumeInfo( 4181): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4181): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4181): getNewCalendarAuthority()...
,D/VolumeInfo( 4181): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4181): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4181): enableAppOperation()+
,D/SyncApplication( 4181): enableAppOperation()-
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4181, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4181, uid=10008, userID:0
,W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 4181): isNeorSinged() + 
,D/HTCUtilities( 4181): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4181): isNeorSinged() return false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/CDMountReceiver( 4181): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4181): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/CDMountReceiver( 4181): enable CD Auto-mount: true
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4181): enable auto-mount
I/ActivityManager(  909): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): releaseWL(426873b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/HTCUtilities( 4181): enable auto-mount
,I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
,D/Process (  909): killProcessQuiet, pid=3586
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  909): Killing 3586:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4202 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42016dd0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 2 26 4 11
,I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41b77ef8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 0 10 3 16
,I/ActivityManager(  909): Recipient 3586
,D/CalendarApplication( 4202): onCreate
D/ProviderChangeReceiver( 4202): ---------------------------------------------------
,D/ProviderChangeReceiver( 4202): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4202): start to updateAlertNotification!
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4216 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  909): killProcessQuiet, pid=3649
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3649:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AlertService( 4202): No fired or scheduled alerts
,D/HtcAlertUtils( 4202): -- cancelReminderNotification --
,D/HtcAlertUtils( 4202): broadcastExistReminder!
I/ActivityManager(  909): Recipient 3649
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4216): [4216/4216] onCreate()
W/ContextImpl( 4216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,D/Process (  909): killProcessQuiet, pid=3910
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3910:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3910
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 9 times.
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=62 rxSum=49} preTxRxSum={txSum=56 rxSum=42}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20716 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20717 delay=15s
D/PMS     (  909): acquireWL(42526478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{426d5f70: PendingIntentRecord{425057d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=75498, Int=0
D/PMS     (  909): releaseWL(42526478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42654570 u0 com.htc.musicenhancer/.EnhancerService}
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:91, mTXpacketCount:90, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  909): releaseWL(42792720): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 10 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/SensorManager(  909): mEventCount = 900
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  909): acquireWL(4261e270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{41cf5920: PendingIntentRecord{42783f78 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455019790537, Int=0
,D/PMS     (  909): releaseWL(4261e270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Finsky  ( 4068): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 11 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/AutoSetting( 1407): service - has update message, not stop
,D/AutoSetting( 1407): service - mHandler: update timezone
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1520): service - mHandler: update timezone
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41bbae60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 7 3 11
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times.
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=63 rxSum=50} preTxRxSum={txSum=62 rxSum=49}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20717 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20718 delay=15s
D/PMS     (  909): acquireWL(425d3840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{424e7288: PendingIntentRecord{425057d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=90506, Int=0
D/PMS     (  909): releaseWL(425d3840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  909): mEventCount = 1050
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:92, mTXpacketCount:91, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  909): acquireWL(4269b508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=93470, Int=0
,D/PMS     (  909): releaseWL(4269b508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1118): now=1455019800056 next=59944
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1520): Don't start project servcice
,D/HtcModeClient( 1520): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1520): connectState: CONNECTION_READY = false
,D/SilentMusic( 1520): call stop
D/HtcModeClient( 1520): close connection
,W/HtcModeClient( 1520): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1520): read the terminate packet, so break
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/SensorManager(  909): mEventCount = 1200
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{426a04c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(427572e8): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
,D/PMS     (  909): releaseWL(427572e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4271ec20): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
,D/PMS     (  909): releaseWL(4271ec20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(42706570): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
,D/PMS     (  909): releaseWL(42706570): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4261afd8): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
,D/PMS     (  909): releaseWL(4261afd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4240 uid=10077 gids={50077}
D/PMS     (  909): acquireWL(42685010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
V/AlarmManager(  909): sending alarm PendingIntent{425602e8: PendingIntentRecord{42418958 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455019811948, Int=60000
,D/PMS     (  909): releaseWL(42685010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4240): SMSBackupAgentService started
,D/SMSBackup( 4240): Checking restore status
,D/SMSBackup( 4240): Restore complete
,D/SMSBackup( 4240): cancelCheckAlarm
,D/SMSBackup( 4240): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=3889
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/ActivityManager(  909): Killing 3889:com.htc.sdm/u0a80 (adj 15): empty #17
D/PMS     (  909): acquireWL(4272e878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42452e30: PendingIntentRecord{425057d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105511, Int=0
,D/PMS     (  909): releaseWL(4272e878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=64 rxSum=51} preTxRxSum={txSum=63 rxSum=50}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20718 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20719 delay=15s
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3889
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:95, mTXpacketCount:92, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  909): mEventCount = 1350
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42100020
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  909): pid=909, uid=1000
,W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42100020, eanble = 0, strlen(mName) = 59
,W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420c0648
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@41ee36e0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  909): mWirelessDisplayManager is null
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 412ms
,W/PnPMgr  (  352): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/PMS     (  909): OOBE c monitor 11
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=1274
V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427941d0)
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/NfcService( 1256): applyRouting -2
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMN     (  909): wakingUp
D/PMS     (  909): acquireWL(426ff4d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  909): releaseWL(426ff4d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): acquireWL(4274d650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(4274d650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMN     (  909): onScreenOn
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiNative-wlan0(  909):    returned true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/MtpService( 2439): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2439): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/NfcService( 1256): applyRouting -2
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20720 delay=15s
D/PMS     (  909): acquireWL(42797f50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/ClockThread( 1118): stop update clock
D/PMS     (  909): releaseWL(42797f50): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4261 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  909): updateScreenOn: false
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(426d2438): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4261 1000 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1812): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1812): onScreenOn: 1455019820566
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1812): onScreenOn: 1455019820566
,D/SmartSyncUtils( 4261): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(426d2f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
D/PMS     (  909): releaseWL(426d2f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420c0648
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420c0648, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@41ee36e0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
,D/PMS     (  909): acquireWL(426f7528): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,I/FeedHostManager( 1274): [onPause]
,I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d82a08
I/SocialFeedProvider( 1274): +onPause
,I/SocialFeedProvider( 1274): -onPause
D/PMS     (  909): releaseWL(426d2438): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20720 mDataStallAlarmIntent=PendingIntent{42415b20: PendingIntentRecord{425057d8 android broadcastIntent}}
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(42777ae0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/PMS     (  909): releaseWL(426f7528): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1407): receiver - intent: android.intent.action.USER_PRESENT
D/SmartSyncUtils( 4261): getMobilePolicyEnabled, result = true
D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3779): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3779): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3779): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3779): Cust_ConnectToPC   : spcsc>false
D/        ( 3779): Cust_ConnectToPC   : IPT>true
D/        ( 3779): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3779): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3779): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3779): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3779): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/SRS_Proc(  370): ParamSet string: screen_state=off
,I/PSReceiver( 3779): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3779): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3779): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3779):  defaultType:0
,D/NetworkPolicy(  909): updateScreenOn: false
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(42777ae0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/Process (  909): killProcessQuiet, pid=3965
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,I/ActivityManager(  909): Killing 3965:com.htc.task.gtask/u0a67 (adj 15): empty #17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Recipient 3965
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4261): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4261): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4261): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1246): start background delete task...
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ee36e0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1246): size: 0 , 0
D/ContactMessageStore( 1246): Background delete complete
,W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ee36e0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ee36e0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ee36e0
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41fbb058 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41fbb058 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1407): service - mHandler: cancel location update
D/AutoSetting( 1407): service -           changes count: 0
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): acquireWL(427ce9c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1812): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1812): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1812): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1812): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1812): onScreenOff
D/PMS     (  909): releaseWL(427ce9c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,I/ActivityManager(  909): Killing 3946:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3946
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3946
,D/Process (  909): killProcessQuiet, pid=3870
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3870:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3870
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(427d6ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(427d6ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(427ddf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41fdb0d0: PendingIntentRecord{420b8ec8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142306, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{4247a998: PendingIntentRecord{4260ffb8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144241, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(427e0060): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1370/10028)
,D/AutoSetting( 1407): service - handleMessage() stop self
D/PMS     (  909): releaseWL(427ddf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  909): acquireWL(427ec998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4db +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  909): releaseWL(427ec998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1407): service - handleMessage() quit looper
,D/AutoSetting( 1407): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=2772
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 2772:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 2772
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 34
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3234302e),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(427e0060): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(428159e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=153470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428159e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2218/10028)
,D/PMS     (  909): acquireWL(42819540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
D/PMS     (  909): releaseWL(42819540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428202e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{4263cf70: PendingIntentRecord{42530880 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=178368, Int=0
,D/PMS     (  909): releaseWL(428202e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(42822538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42822538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42829980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=213470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42829980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4282bc20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4282bc20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42832be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42832be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(4283a028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=273470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4283a028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(4283c2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(4283c2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428436f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=333470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428436f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42845990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42845990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4294 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  909): acquireWL(428483f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10047}
,V/AlarmManager(  909): sending alarm PendingIntent{4245fff8: PendingIntentRecord{420b89f0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455019927943, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{4272cb20: PendingIntentRecord{4272cac0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1455020067195, Int=0
,D/PMS     (  909): releaseWL(428483f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4294/10047)
,W/Uploader( 2218): No account for auth token provided
,D/Process (  909): killProcessQuiet, pid=4022
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4022:com.google.android.talk/u0a111 (adj 15): empty #17
,D/libc    ( 2218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2218): [NET] getaddrinfo-,err=8
D/libc    ( 2218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2218): [NET] getaddrinfo-, 1
,D/libc    ( 2218): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e0ae +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4022
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2218): [NET] getaddrinfo_proxy-, success
,I/global  ( 2218): call createSocket() return a new socket.
D/libc    ( 2218): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2218): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2218): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2218/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2218/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2218/10028)
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1370): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1370): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1370): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1370): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1370): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1370): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1370): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1370): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,E/PlayEventLogger( 4068): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4068): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4068): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4068): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4068): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4068): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4068): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4068): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41defec0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 3 11 3 12
,D/libc    ( 4068): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4068): [NET] getaddrinfo-,err=8
D/libc    ( 4068): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4068): [NET] getaddrinfo-, 1
,D/libc    ( 4068): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4e09 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4068): [NET] getaddrinfo_proxy-, success
I/global  ( 4068): call createSocket() return a new socket.
D/libc    ( 4068): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4068): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4068): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4068): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(42708360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42708360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(426fd558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=393470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(426fd558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(426fb848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426fb848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(426a2ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426a2ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4269fc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=453470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4269fc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(4269f428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(4269f428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(4262f178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4262f178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(425c7f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=513470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(425c7f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(425c7838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
D/PMS     (  909): releaseWL(425c7838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  391): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42090d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(42090d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(41dc91a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=573470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41dc91a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(423d21d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(423d21d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(421dd4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(421dd4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1246): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1246): mDeleteTask = null, bDeleting = false
,D/ContactMessageStore( 1246): start background delete task...
D/AccFlag ( 1246): sku_id=99
,D/ContactMessageStore( 1246): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1165): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1165): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1165): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
,I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1165): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1165): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1165): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000629334745
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000629334708
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000629334735
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000000629334755
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42052a80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42052a80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42052a80 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0,
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 629334745, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 629334708, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 629334735, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 629334755, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==,
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42584c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=633470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42584c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1165): Add randomness: count=16 entropy=9
D/wpa_supplicant( 1165): Add randomness: count=17 entropy=10
D/wpa_supplicant( 1165): Add randomness: count=18 entropy=11
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=19 entropy=12
D/wpa_supplicant( 1165): Add randomness: count=20 entropy=13
D/wpa_supplicant( 1165): Add randomness: count=21 entropy=14
D/wpa_supplicant( 1165): Add randomness: count=22 entropy=15
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000647521879
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000647521844
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000647521869
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000647521889
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 647521879, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 647521844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 647521869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 647521889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4283da00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4283da00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo,
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=23 entropy=16
D/wpa_supplicant( 1165): Add randomness: count=24 entropy=17
D/wpa_supplicant( 1165): Add randomness: count=25 entropy=18
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=26 entropy=19
D/wpa_supplicant( 1165): Add randomness: count=27 entropy=20
D/wpa_supplicant( 1165): Add randomness: count=28 entropy=21
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000665764637
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000665764611
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000647521869
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000665764648
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 665764637, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 665764611, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 647521869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 665764648, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/Process (  909): killProcessQuiet, pid=3559
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3559:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3559
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42820198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(42820198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available,
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=29 entropy=22
D/wpa_supplicant( 1165): Add randomness: count=30 entropy=23
D/wpa_supplicant( 1165): Add randomness: count=31 entropy=24
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=32 entropy=25
D/wpa_supplicant( 1165): Add randomness: count=33 entropy=26
D/wpa_supplicant( 1165): Add randomness: count=34 entropy=27
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant,( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000683984696
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000683984670
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000683984707
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0,
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 683984696, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 683984670, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 683984707, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42643d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=693470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42643d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=35 entropy=28
D/wpa_supplicant( 1165): Add randomness: count=36 entropy=29
D/wpa_supplicant( 1165): Add randomness: count=37 entropy=30
D/wpa_supplicant( 1165): Add randomness: count=38 entropy=31
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
,I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=39 entropy=32
D/wpa_supplicant( 1165): Add randomness: count=40 entropy=33
D/wpa_supplicant( 1165): Add randomness: count=41 entropy=34
D/wpa_supplicant( 1165): Add randomness: count=42 entropy=35
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (518) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000702284743
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000702284716
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000702284754
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000000702284762
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC0039325
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 702284743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 702284716, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 702284754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 702284762, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults,
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(426ff830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426ff830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=43 entropy=36
D/wpa_supplicant( 1165): Add randomness: count=44 entropy=37
D/wpa_supplicant( 1165): Add randomness: count=45 entropy=38
D/wpa_supplicant( 1165): Add randomness: count=46 entropy=39
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=47 entropy=40
D/wpa_supplicant( 1165): Add randomness: count=48 entropy=41
D/wpa_supplicant( 1165): Add randomness: count=49 entropy=42
D/wpa_supplicant( 1165): Add randomness: count=50 entropy=43
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (518) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000720292173
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000720292148
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000720292184
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1165): freq=2462,
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000000720292193
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC0039325
I/wpa_supplicant( 1165): ####
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 720292173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 720292148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 720292184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 720292193, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4283ea40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4283ea40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=51 entropy=44
D/wpa_supplicant( 1165): Add randomness: count=52 entropy=45
D/wpa_supplicant( 1165): Add randomness: count=53 entropy=46
D/wpa_supplicant( 1165): Add randomness: count=54 entropy=47
D/wpa_supplicant( 1165): Add randomness: count=55 entropy=48
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplica,nt( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=56 entropy=49
D/wpa_supplicant( 1165): Add randomness: count=57 entropy=50
D/wpa_supplicant( 1165): Add randomness: count=58 entropy=51
D/wpa_supplicant( 1165): Add randomness: count=59 entropy=52
D/wpa_supplicant( 1165): Add randomness: count=60 entropy=53
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (631) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000738322033
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000720292148
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
,I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000738322045
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000000738322054
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC0039325
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000738322021
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 738322033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 720292148, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 738322045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 738322054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 738322021, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42072a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=753471, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42072a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=61 entropy=54
D/wpa_supplicant( 1165): Add randomness: count=62 entropy=55
D/wpa_supplicant( 1165): Add randomness: count=63 entropy=56
D/wpa_supplicant( 1165): Add randomness: count=64 entropy=57
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=65 entropy=58
D/wpa_supplicant( 1165): Add randomness: count=66 entropy=59
D/wpa_supplicant( 1165): Add randomness: count=67 entropy=60
D/wpa_supplicant( 1165): Add randomness: count=68 entropy=61
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (631) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000756661424
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000756661387
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g,
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000756661434
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000000738322054
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC0039325
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000756661413
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 756661424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 756661387, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 756661434, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 738322054, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 756661413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=69 entropy=62
D/wpa_supplicant( 1165): Add randomness: count=70 entropy=63
D/wpa_supplicant( 1165): Add randomness: count=71 entropy=64
D/wpa_supplicant( 1165): Add randomness: count=72 entropy=65
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=73 entropy=66
D/wpa_supplicant( 1165): Add randomness: count=74 entropy=67
D/wpa_supplicant( 1165): Add randomness: count=75 entropy=68
D/wpa_supplicant( 1165): Add randomness: count=76 entropy=69
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
,I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000774931760
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4,
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000774931722
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412,
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000774931771
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000774931750
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
,I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList,
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 774931760, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 774931722, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 774931771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 774931750, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4284ef70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4284ef70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42855fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42855fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=77 entropy=70
D/wpa_supplicant( 1165): Add randomness: count=78 entropy=71
D/wpa_supplicant( 1165): Add randomness: count=79 entropy=72
D/wpa_supplicant( 1165): Add randomness: count=80 entropy=73
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=81 entropy=74
D/wpa_supplicant( 1165): Add randomness: count=82 entropy=75
D/wpa_supplicant( 1165): Add randomness: count=83 entropy=76
D/wpa_supplicant( 1165): Add randomness: count=84 entropy=77
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2,
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000793132170
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000793132132
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000793132180
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000793132158
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0,
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 793132170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 793132132, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 793132180, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 793132158, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=85 entropy=78
D/wpa_supplicant( 1165): Add randomness: count=86 entropy=79
D/wpa_supplicant( 1165): Add randomness: count=87 entropy=80
D/wpa_supplicant( 1165): Add randomness: count=88 entropy=81
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=89 entropy=82
D/wpa_supplicant( 1165): Add randomness: count=90 entropy=83
D/wpa_supplicant( 1165): Add randomness: count=91 entropy=84
D/wpa_supplicant( 1165): Add randomness: count=92 entropy=85
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000811172033
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====,
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000811171996
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-87
I/wpa_supplicant( 1165): tsf=0000000811172043
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
,I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000811172022
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiP2pService(  909): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 811172033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 811171996, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 811172043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 811172022, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4288c488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=813471, Int=0,
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4288c488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=93 entropy=86
D/wpa_supplicant( 1165): Add randomness: count=94 entropy=87
D/wpa_supplicant( 1165): Add randomness: count=95 entropy=88
D/wpa_supplicant( 1165): Add randomness: count=96 entropy=89
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=241,2 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=97 entropy=90
D/wpa_supplicant( 1165): Add randomness: count=98 entropy=91
D/wpa_supplicant( 1165): Add randomness: count=99 entropy=92
D/wpa_supplicant( 1165): Add randomness: count=100 entropy=93
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000829392122
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000829392085
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000829392132
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000829392111
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 829392122, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 829392085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 829392132, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 829392111, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(428a5c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428a5c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-,
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=101 entropy=94
D/wpa_supplicant( 1165): Add randomness: count=102 entropy=95
D/wpa_supplicant( 1165): Add randomness: count=103 entropy=96
D/wpa_supplicant( 1165): Add randomness: count=104 entropy=97
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=105 entropy=98
D/wpa_supplicant( 1165): Add randomness: count=106 entropy=99
D/wpa_supplicant( 1165): Add randomness: count=107 entropy=100
D/wpa_supplicant( 1165): Add randomness: count=108 entropy=101
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000847604765
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000847604726
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000847604775
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000847604754
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 847604765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 847604726, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 847604775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 847604754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==,
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(428c41a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(428c41a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available,
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=109 entropy=102
D/wpa_supplicant( 1165): Add randomness: count=110 entropy=103
D/wpa_supplicant( 1165): Add randomness: count=111 entropy=104
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
,I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
,D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=112 entropy=105
D/wpa_supplicant( 1165): Add randomness: count=113 entropy=106
D/wpa_supplicant( 1165): Add randomness: count=114 entropy=107
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000865844684
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000865844658
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
,I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000865844695
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=8
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000847604754
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 865844684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 865844658, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 865844695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 847604754, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/PMS     (  909): acquireWL(428e2b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=873470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428e2b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=115 entropy=108
D/wpa_supplicant( 1165): Add randomness: count=116 entropy=109
D/wpa_supplicant( 1165): Add randomness: count=117 entropy=110
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=118 entropy=111
D/wpa_supplicant( 1165): Add randomness: count=119 entropy=112
D/wpa_supplicant( 1165): Add randomness: count=120 entropy=113
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  909): getDiscoveryDongleList
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000884094923
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000884094897
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
,I/wpa_supplicant( 1165): tsf=0000000884094934
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 884094923, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 884094897, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 884094934, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/PMS     (  909): acquireWL(428f8ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(428f8ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=121 entropy=114
D/wpa_supplicant( 1165): Add randomness: count=122 entropy=115
D/wpa_supplicant( 1165): Add randomness: count=123 entropy=116
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=124 entropy=117
D/wpa_supplicant( 1165): Add randomness: count=125 entropy=118
D/wpa_supplicant( 1165): Add randomness: count=126 entropy=119
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000902135136
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000902135109
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000902135147
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 902135136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 902135109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 902135147, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 3 to mScanResults,
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42914218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42914218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=127 entropy=120
D/wpa_supplicant( 1165): Add randomness: count=128 entropy=121
D/wpa_supplicant( 1165): Add randomness: count=129 entropy=122
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=130 entropy=123
D/wpa_supplicant( 1165): Add randomness: count=131 entropy=124
D/wpa_supplicant( 1165): Add randomness: count=132 entropy=125
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000920385184
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000920385157
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000920385195
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 920385184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 920385157, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 920385195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4292f890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=933470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4292f890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=133 entropy=126
D/wpa_supplicant( 1165): Add randomness: count=134 entropy=127
D/wpa_supplicant( 1165): Add randomness: count=135 entropy=128
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=136 entropy=129
D/wpa_supplicant( 1165): Add randomness: count=137 entropy=130
D/wpa_supplicant( 1165): A,dd randomness: count=138 entropy=131
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000938371922
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000938371896
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000938371933
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 938371922, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 938371896, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 938371933, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42945d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42945d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=139 entropy=132
D/wpa_supplicant( 1165): Add randomness: count=140 entropy=133
D/wpa_supplicant( 1165): Add randomness: count=141 entropy=134
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=142 entropy=135
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): Add randomness: count=143 entropy=136
D/wpa_supplicant( 1165): Add randomness: count=144 entropy=137
D/WifiNative-,wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000956668914
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000956668888
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000956668925
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0,
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 956668914, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 956668888, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 956668925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(42961160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42961160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=145 entropy=138
D/wpa_supplicant( 1165): Add randomness: count=146 entropy=139
D/wpa_supplicant( 1165): Add randomness: count=147 entropy=140
D/wpa_supplicant( 1165): Add randomness: count=148 entropy=141
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=149 entropy=142
D/wpa_supplicant( 1165): Add randomness: count=150 entropy=143
D/wpa_supplicant( 1165): Add randomness: count=151 entropy=144
D/wpa_supplicant( 1165): Add randomness: count=152 entropy=145
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2,
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000974924346
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000974924309
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000974924356
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000974924334
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 974924346, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 974924309, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 974924356, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 974924334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=153 entropy=146
D/wpa_supplicant( 1165): Add randomness: count=154 entropy=147
D/wpa_supplicant( 1165): Add randomness: count=155 entropy=148
D/wpa_supplicant( 1165): Add randomness: count=156 entropy=149
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=157 entropy=150
D/wpa_supplicant( 1165): Add randomness: count=158 entropy=151
D/wpa_supplicant( 1165): Add randomness: count=159 entropy=152
D/wpa_supplicant( 1165): Add randomness: count=160 entropy=153
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000000993251901
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000993251864
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000993251911
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000993251890
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 993251901, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 993251864, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 993251911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 993251890, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42989f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=993471, Int=0
,D/PMS     (  909): releaseWL(42989f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=161 entropy=154
D/wpa_supplicant( 1165): Add randomness: count=162 entropy=155
D/wpa_supplicant( 1165): Add randomness: count=163 entropy=156
D/wpa_supplicant( 1165): Add randomness: count=164 entropy=157
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1165): wpa_s->reassociate is 0
,I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1165): Add randomness: count=165 entropy=158
D/wpa_supplicant( 1165): Add randomness: count=166 entropy=159
D/wpa_supplicant( 1165): Add randomness: count=167 entropy=160
D/wpa_supplicant( 1165): Add randomness: count=168 entropy=161
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001011494815
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001011494779
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g,
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001011494825
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000001011494805
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1011494815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1011494779, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1011494825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1011494805, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(426e4930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  909): sending alarm PendingIntent{41dda0a0: PendingIntentRecord{42486558 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787557, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{420652c8: PendingIntentRecord{420a5c90 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=929217, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{425522f0: PendingIntentRecord{425b5278 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455020648276, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{424c28f8: PendingIntentRecord{426f7248 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455020720709, Int=0
,D/PMS     (  909): acquireWL(426cd400): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10028 null
D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,D/PMS     (  909): releaseWL(426cd400): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,W/ContextImpl( 4261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): acquireWL(426c9e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  909): releaseWL(426c9e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PowerUsageService( 4261): call getInstance()
D/SmartSyncUtils( 4261): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4261): MY_DEBUG = false
D/PMS     (  909): acquireWL(426c9a00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4261 1000 null
,D/PMS     (  909): releaseWL(426e4930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4261): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4261): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4261): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4261): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081441000
D/SmartSyncScreenOnOffTimeReceiver( 4261): SettingOffTime = 1455062400000, randomSettingOffTime = 1455068001000
D/SmartSyncScreenOnOffTimeReceiver( 4261): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4261): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4261): bNightModeTurnOffOnce = false
D/PMS     (  909): releaseWL(426c9a00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(42892198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PMS     (  909): releaseWL(42892198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4252f6a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,D/GCM     ( 1370): Message class mow
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1370/10028)
,D/PMS     (  909): releaseWL(4252f6a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): acquireWL(41eae6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  909): releaseWL(41eae6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=169 entropy=162
D/wpa_supplicant( 1165): Add randomness: count=170 entropy=163
D/wpa_supplicant( 1165): Add randomness: count=171 entropy=164
D/wpa_supplicant( 1165): Add randomness: count=172 entropy=165
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=173 entropy=166
D/wpa_supplicant( 1165): Add randomness: count=174 entropy=167
D/wpa_supplicant( 1165): Add randomness: count=175 entropy=168
D/wpa_supplicant( 1165): Add randomness: count=176 entropy=169
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001029745004
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001029744967
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001029745014
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001029744994
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1029745004, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1029744967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1029745014, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1029744994, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4278b588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4278b588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=177 entropy=170
D/wpa_supplicant( 1165): Add randomness: count=178 entropy=171
D/wpa_supplicant( 1165): Add randomness: count=179 entropy=172
D/wpa_supplicant( 1165): Add randomness: count=180 entropy=173
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=181 entropy=174
D/wpa_supplicant( 1165): Add randomness: count=182 entropy=175
D/wpa_supplicant( 1165): Add randomness: count=183 entropy=176
D/wpa_supplicant( 1165): Add randomness: count=184 entropy=177
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001047922337,
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001047922299
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
,I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001047922346
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
,I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001047922326
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1047922337, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1047922299, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1047922346, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1047922326, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4272f470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1053470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4272f470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=185 entropy=178
D/wpa_supplicant( 1165): Add randomness: count=186 entropy=179
D/wpa_supplicant( 1165): Add randomness: count=187 entropy=180
D/wpa_supplicant( 1165): Add randomness: count=188 entropy=181
D/wpa_supplicant( 1165): Add randomness: count=189 entropy=182
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=190 entropy=183
D/wpa_supplicant( 1165): Add randomness: count=191 entropy=184
D/wpa_supplicant( 1165): Add randomness: count=192 entropy=185
D/wpa_supplicant( 1165): Add randomness: count=193 entropy=186
D/wpa_supplicant( 1165): Add randomness: count=194 entropy=187
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (614) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001066144743
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001066144707
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001066144753
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001066144733
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=10
I/wpa_supplicant( 1165): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000001066144762
I/wpa_supplicant( 1165): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1066144743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1066144707, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1066144753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1066144733, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1066144762, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4275cb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(4275cb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=195 entropy=188
D/wpa_supplicant( 1165): Add randomness: count=196 entropy=189
D/wpa_supplicant( 1165): Add randomness: count=197 entropy=190
D/wpa_supplicant( 1165): Add randomness: count=198 entropy=191
D/wpa_supplicant( 1165): Add randomness: count=199 entropy=192
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54,
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=200 entropy=193
D/wpa_supplicant( 1165): Add randomness: count=201 entropy=194
D/wpa_supplicant( 1165): Add randomness: count=202 entropy=195
D/wpa_supplicant( 1165): Add randomness: count=203 entropy=196
D/wpa_supplicant( 1165): Add randomness: count=204 entropy=197
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
,W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (614) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
,I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001084404694
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001084404657
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001084404704
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-50
I/wpa_supplicant( 1165): tsf=0000001084404683
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====,
I/wpa_supplicant( 1165): id=10
I/wpa_supplicant( 1165): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000001084404712
I/wpa_supplicant( 1165): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1084404694, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1084404657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1084404704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1084404683, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1084404712, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42821950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42821950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter,
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=205 entropy=198
D/wpa_supplicant( 1165): Add randomness: count=206 entropy=199
D/wpa_supplicant( 1165): Add randomness: count=207 entropy=200
D/wpa_supplicant( 1165): Add randomness: count=208 entropy=201
D/wpa_supplicant( 1165): Add randomness: count=209 entropy=202
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wp,a_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1165): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=210 entropy=203
D/wpa_supplicant( 1165): Add randomness: count=211 entropy=204
D/wpa_supplicant( 1165): Add randomness: count=212 entropy=205
D/wpa_supplicant( 1165): Add randomness: count=213 entropy=206
D/wpa_supplicant( 1165): Add randomness: count=214 entropy=207
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (614) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001102664708
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001102664671
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001102664718
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-50
I/wpa_supplicant( 1165): tsf=0000001102664698
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=10
I/wpa_supplicant( 1165): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000001102664727
I/wpa_supplicant( 1165): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1102664708, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiP2pService(  909): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1102664671, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1102664718, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1102664698, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  909): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1102664727, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4288ac70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1113470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4288ac70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=215 entropy=208
D/wpa_supplicant( 1165): Add randomness: count=216 entropy=209
D/wpa_supplicant( 1165): Add randomness: count=217 entropy=210
D/wpa_supplicant( 1165): Add randomness: count=218 entropy=211
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
,I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=219 entropy=212
D/wpa_supplicant( 1165): Add randomness: count=220 entropy=213
D/wpa_supplicant( 1165): Add randomness: count=221 entropy=214
D/wpa_supplicant( 1165): Add randomness: count=222 entropy=215
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (614) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001120914779
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001102664671
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001120914789
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-50
I/wpa_supplicant( 1165): tsf=0000001120914768
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=10
I/wpa_supplicant( 1165): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-91
I/wpa_supplicant( 1165): tsf=0000001102664727
I/wpa_supplicant( 1165): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1120914779, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1102664671, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1120914789, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1120914768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1102664727, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 5 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList,
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (5) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  909): acquireWL(4282e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4282e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=223 entropy=216
D/wpa_supplicant( 1165): Add randomness: count=224 entropy=217
D/wpa_supplicant( 1165): Add randomness: count=225 entropy=218
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=226 entropy=219
D/wpa_supplicant( 1165): Add randomness: count=227 entropy=220
D/wpa_supplicant( 1165): Add randomness: count=228 entropy=221
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001139211752
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001139211726
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001139211765
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=9
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-50
I/wpa_supplicant( 1165): tsf=0000001120914768
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1139211752, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1139211726, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1139211765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 1120914768, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/PMS     (  909): acquireWL(427cc7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  909): releaseWL(427cc7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=229 entropy=222
D/wpa_supplicant( 1165): Add randomness: count=230 entropy=223
D/wpa_supplicant( 1165): Add randomness: count=231 entropy=224
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32,
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47,
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0,
D/wpa_supplicant( 1165): Add randomness: count=232 entropy=225
D/wpa_supplicant( 1165): Add randomness: count=233 entropy=226
D/wpa_supplicant( 1165): Add randomness: count=234 entropy=227
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  909): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (376) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001157434601
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001157434575
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000001157434612
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ####
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiP2pService(  909): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1157434601, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1157434575, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 1157434612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
,D/WifiP2pService(  909): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter,
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  909): acquireWL(4285e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1173470, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4285e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=235 entropy=228
D/wpa_supplicant( 1165): Add randomness: count=236 entropy=229
D/wpa_supplicant( 1165): Add randomness: count=237 entropy=230
D/wpa_supplicant( 1165): Add randomness: count=238 entropy=231
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=239 entropy=232
D/wpa_supplicant( 1165): Add randomness: count=240 entropy=233
D/wpa_supplicant( 1165): Add randomness: count=241 entropy=234
D/wpa_supplicant( 1165): Add randomness: count=242 entropy=235
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (490) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001175748819
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001175748781
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001175748830
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001175748807
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1175748819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1175748781, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1175748830, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1175748807, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=243 entropy=236
D/wpa_supplicant( 1165): Add randomness: count=244 entropy=237
D/wpa_supplicant( 1165): Add randomness: count=245 entropy=238
D/wpa_supplicant( 1165): Add randomness: count=246 entropy=239
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 ,freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=247 entropy=240
D/wpa_supplicant( 1165): Add randomness: count=248 entropy=241
D/wpa_supplicant( 1165): Add randomness: count=249 entropy=242
D/wpa_supplicant( 1165): Add randomness: count=250 entropy=243
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (490) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001194032069
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001194032031
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001194032079
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001194032057
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=1,47461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1194032069, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1194032031, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1194032079, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1194032057, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1,
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(426b5fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(426b5fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=251 entropy=244
D/wpa_supplicant( 1165): Add randomness: count=252 entropy=245
D/wpa_supplicant( 1165): Add randomness: count=253 entropy=246
D/wpa_supplicant( 1165): Add randomness: count=254 entropy=247
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1165): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=255 entropy=248
D/wpa_supplicant( 1165): Add randomness: count=256 entropy=249
D/wpa_supplicant( 1165): Add randomness: count=257 entropy=250
D/wpa_supplicant( 1165): Add randomness: count=258 entropy=251
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (490) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001212242145
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001212242108
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001212242156
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001212242134
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0,
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1212242145, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1212242108, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1212242156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1212242134, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 4 to mScanResults
,V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42955380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED,
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42955380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=259 entropy=252
D/wpa_supplicant( 1165): Add randomness: count=260 entropy=253
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=261 entropy=254
D/wpa_supplicant( 1165): Add randomness: count=262 entropy=255
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (490) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001230302113
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001230302085
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000001212242156
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001212242134
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1230302113, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1230302085, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  909):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1212242156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1212242134, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(426b1db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000},
,V/AlarmManager(  909): sending alarm PendingIntent{423d00c0: PendingIntentRecord{423ba4e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1233470, Int=0,
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  909): releaseWL(426b1db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=263 entropy=256
D/wpa_supplicant( 1165): Add randomness: count=264 entropy=257
D/wpa_supplicant( 1165): Add randomness: count=265 entropy=258
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=266 entropy=259
D/wpa_supplicant( 1165): Add randomness: count=267 entropy=260
D/wpa_supplicant( 1165): Add randomness: count=268 entropy=261
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelemen,t id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (352) for get BSS: id=2,
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001248552285
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001248552247
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412,
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001248552273
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  909):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1248552285, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1248552247, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1248552273, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  909): add 3 to mScanResults
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4276e3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  909): releaseWL(4276e3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=269 entropy=262
D/wpa_supplicant( 1165): Add randomness: count=270 entropy=263
D/wpa_supplicant( 1165): Add randomness: count=271 entropy=264
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -54
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters,
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1165): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=272 entropy=265
,D/wpa_supplicant( 1165): Add randomness: count=273 entropy=266
D/wpa_supplicant( 1165): Add randomness: count=274 entropy=267
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (352) for get BSS: id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001266774798
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000001266774761
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====,
I/wpa_supplicant( 1165): id=11
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-54
I/wpa_supplicant( 1165): tsf=0000001266774788
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -54, 0
D/WifiP2pService(  909): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 1266774798, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1266774761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1266774788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4297ac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4297ac08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4350): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4350): ====startRecUseTime====
D/htc.customization.log.level( 4350):  is 
W/CustomizationLogLevel( 4350): Level value is invalid, use default level 2
D/CustomizationManager( 4350):  Read ACC file spent 0.109 (s)
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4350): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4350): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4350): Parsing tag category name = system
I/CustomizationCIDLoader( 4350): Parsing tag category name = application
I/CustomizationCIDLoader( 4350): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4350): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4350): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4350): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4350): Parsing tag category name = Settings
D/CustomizationManager( 4350):  Read CID file spent 0.162 (s)
D/CustomizationManager( 4350):  All configurations done spent 0.162 (s)
W/HtcNativeFlag( 4350): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4350): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4350): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4350): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4350, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  909): Skipping PackageSetting{422d9ea8 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  909): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  909): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1437): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(42945fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
D/PMS     (  909): releaseWL(42945fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/acms    ( 1876): Unregistering com.test.thalitest
E/acms    ( 1876): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PackageBroadcastService( 2218): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4364 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  909): Delaying start of: ServiceRecord{427ec650 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4364): install
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/MultiDex( 4364): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4364): loading existing secondary dex files
I/MultiDex( 4364): load found 1 secondary dex files
I/MultiDex( 4364): install done
I/PeopleContactsSync( 2218): CP2 sync disabled
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2218, uid=10028, userID:0
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
F/PackageManager(  909): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  909): java.io.IOException: write failed: EROFS (Read-only file system)
F/PackageManager(  909): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  909): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  909): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  909): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  909): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  909): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  909): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  909): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  909): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1203)
F/PackageManager(  909): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  909): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  909): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  909): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  909): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  909): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  909): Caused by: libcore.io.ErrnoException: write failed: EROFS (Read-only file system)
F/PackageManager(  909): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  909): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  909): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  909): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  909): 	... 14 more
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  909): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1455020988336.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/ErrorReport(  909): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  909): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
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
D/PMS     (  909): acquireWL(42407978): PARTIAL_WAKE_LOCK  Icing 0x1 2218 10028 null
I/Icing   ( 2218): doRemovePackageData com.test.thalitest
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.corpusid-1
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2218): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2218): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2218): Writing status failed
D/PMS     (  909): releaseWL(42407978): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4386 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4364): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 2218): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2218): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2218): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2218): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2218): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2218): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2218): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2218): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4386): install
E/ClearPendingStateOp( 2218): Runtime exception while performing operation
E/ClearPendingStateOp( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2218): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2218): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2218): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2218): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2218): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2218): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2218): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4386): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
F/ClearPendingStateOp( 2218): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2218): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2218): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2218): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2218): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2218): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2218): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2218): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4386): loading existing secondary dex files
I/MultiDex( 4386): load found 1 secondary dex files
I/MultiDex( 4386): install done
E/DropBoxManagerService(  909): Can't write: system_app_wtf
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 4386): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1407): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SharedPreferencesImpl( 1211): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/SQLiteLog( 1407): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1407): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c8c1010
W/[PluginManager]RegisterService( 1407): provider may killed!
W/[PluginManager]RegisterService( 1407): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1407): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1407): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1407): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Resuming delayed broadcast
E/SQLiteDatabase( 4364): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4364): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4364): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4364): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4364): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4364): threadid=12: thread exiting with uncaught exception (group=0x41718e30)
E/AndroidRuntime( 4364): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4364): Process: com.google.android.gms.drive, PID: 4364
E/AndroidRuntime( 4364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4364): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4364): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4364): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4364): 	at ctn.run(SourceFile:985)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/Process ( 4364): killProcess, pid=4364
D/Process ( 4364): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 2911): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2911): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x647c10b8
W/dalvikvm( 2911): threadid=14: thread exiting with uncaught exception (group=0x41718e30)
I/ActivityManager(  909): Recipient 4364
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4364) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  909): Resuming delayed broadcast
E/AndroidRuntime( 2911): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2911): Process: com.google.android.googlequicksearchbox:search, PID: 2911
E/AndroidRuntime( 2911): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2911): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2911): 	at cid.d(PG:186)
E/AndroidRuntime( 2911): 	at clo.g(PG:594)
E/AndroidRuntime( 2911): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2911): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2911): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2911): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2911): 	at clr.tL(PG:827)
E/AndroidRuntime( 2911): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2911): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2911): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2911): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2911): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4407 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process ( 2911): killProcess, pid=2911
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2911): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/SQLiteConnectionPool( 2218): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2218): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2218): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  909): Recipient 2911
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.googlequicksearchbox:search (pid 2911) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
D/MediaRouterService(  909): Client com.google.android.googlequicksearchbox (pid 2911): Died!
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/WifiService(  909): Client connection lost with reason: 4
E/SQLiteDatabase( 2218): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2218): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2218): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2218): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2218): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2218): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2218): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2218): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2218): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2218): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2218): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2218): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2218): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2218): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2218): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2218): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2218): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2218): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2218): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2218): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2218): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2218): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2218): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2218): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2218): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2218): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2218): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2218): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2218): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2218): threadid=10: thread exiting with uncaught exception (group=0x41718e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2218): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2218): Process: com.google.android.gms, PID: 2218
E/AndroidRuntime( 2218): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2218): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2218): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2218): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2218): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2218): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2218): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2218): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2218): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  909): killProcessQuiet, pid=2218
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  909): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  909): Killing 2218:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4407): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4407): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4407): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4407): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4407): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4407): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4407): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4407): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4407): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4407): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4407): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4407): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4407): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4407): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4407): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4407): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4407): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4407): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4407): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4407): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4407): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4407): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4407): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4407): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4407): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4407): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4407): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4407): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4407): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4407): threadid=11: thread exiting with uncaught exception (group=0x41718e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4407): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4407): Process: com.google.android.apps.docs, PID: 4407
E/AndroidRuntime( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4407): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4407): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4407): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4407): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4407): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  909): Can't write: system_app_crash
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
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4407): 	at com.andro,id.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4407): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4407): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4407): 	at dalvik.system.NativeStart.main(Native Method)

```
