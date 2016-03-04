#### Test 61699762a45f11c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1453): handler message = 4011
E/HtcModeClient( 1453): Check connection and retry 9 times.
,E/cutils-trace( 3741): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3741): ====startRecUseTime====
D/htc.customization.log.level( 3741):  is 
W/CustomizationLogLevel( 3741): Level value is invalid, use default level 2
D/CustomizationManager( 3741):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3741): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3741): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3741): Parsing tag category name = system
I/CustomizationCIDLoader( 3741): Parsing tag category name = application
I/CustomizationCIDLoader( 3741): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3741): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3741): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3741): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3741): Parsing tag category name = Settings
D/CustomizationManager( 3741):  Read CID file spent 0.100 (s)
D/CustomizationManager( 3741):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 3741): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3741): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3741): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3741): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3741
,D/PMS     (  902): acquireWL(420a7000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10073}
,V/AlarmManager(  902): sending alarm PendingIntent{420950d0: PendingIntentRecord{42747778 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457092487250, Int=0
,D/PMS     (  902): releaseWL(420a7000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3593): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 1453): handler message = 4011
,E/HtcModeClient( 1453): Check connection and retry 10 times.
,D/AutoSetting( 1370): service - handleMessage() stop self
,D/AutoSetting( 1370): service - handleMessage() quit looper
,D/AutoSetting( 1370): service - onDestroy() END
,D/Process (  902): killProcessQuiet, pid=3431
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3431:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3431
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  902): mEventCount = 900
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
D/PMS     (  902): acquireWL(425e9970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{422548b0: PendingIntentRecord{42048748 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81092, Int=0
D/PMS     (  902): releaseWL(425e9970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1453): handler message = 4011
,E/HtcModeClient( 1453): Check connection and retry 11 times.
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1453): handler message = 4011
,E/HtcModeClient( 1453): Check connection and retry 12 times.
,D/PMS     (  902): acquireWL(425bcee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=89751, Int=0
,D/PMS     (  902): releaseWL(425bcee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1104): now=1457092500060 next=59940
,I/SensorManager(  902): mEventCount = 1050
,D/PMS     (  902): acquireWL(426922c8): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
,D/PMS     (  902): releaseWL(426922c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(4257f968): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
,D/PMS     (  902): releaseWL(4257f968): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(4262c648): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
,D/PMS     (  902): releaseWL(4262c648): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(41f9e490): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
,D/PMS     (  902): releaseWL(41f9e490): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/HtcModeClient( 1453): handler message = 4011
,E/HtcModeClient( 1453): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1453): Don't start project servcice
,D/HtcModeClient( 1453): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1453): connectState: CONNECTION_READY = false
D/SilentMusic( 1453): call stop
D/HtcModeClient( 1453): close connection
,W/HtcModeClient( 1453): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1453): read the terminate packet, so break
,D/Process (  902): killProcessQuiet, pid=3459
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3459:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3459
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  902): Client connection lost with reason: 4
,I/SensorManager(  902): mEventCount = 1200
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3757 uid=10077 gids={50077}
,D/PMS     (  902): acquireWL(426b32e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10077}
,V/AlarmManager(  902): sending alarm PendingIntent{4251a298: PendingIntentRecord{4256ea58 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457092513678, Int=60000
,D/PMS     (  902): releaseWL(426b32e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3757): SMSBackupAgentService started
,D/SMSBackup( 3757): Checking restore status
,D/SMSBackup( 3757): Restore complete
,D/SMSBackup( 3757): cancelCheckAlarm
,D/SMSBackup( 3757): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  902): killProcessQuiet, pid=2527
,I/ActivityManager(  902): Killing 2527:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 2527
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  902): mEventCount = 1350
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f7828
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
W/SensorService(  902): pid=902, uid=1000
,D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f7828, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42350d10
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@4261fca8
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  902): mWirelessDisplayManager is null
W/BatSI   (  902): Couldn't get kernel wake lock stats
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
V/LightsService(  902): setLight #0: color=#0
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 416ms
,W/PnPMgr  (  349): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,D/NfcService( 1224): ScreenObserver: OFF
,D/NfcService( 1224): applyRouting - 0
D/PMS     (  902): nativeSetInteractive:false
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
D/HABCtrl (  902): TPE algorithm. remove timeout.
D/PMS     (  902): OOBE c monitor 11
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
I/InputMethodManagerService(  902): Disable input method client, pid=1238
V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425db098)
,D/NfcService( 1224): applyRouting -2
,I/IntentController( 1104): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
D/PMS     (  902): acquireWL(426d6940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1224 1027 null
D/PMN     (  902): wakingUp
D/PMS     (  902): releaseWL(426d6940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/XT9_C   ( 1179): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1179): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WindowManager(  902): No lock screen! windowToken=null
D/PMS     (  902): acquireWL(426ed188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  902): releaseWL(426ed188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMN     (  902): onScreenOn
D/MtpService( 2205): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1224): applyRouting - 0
,D/MtpService( 2205): [MTP][onReceive]-
,D/AutoSetting( 1370): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1224): applyRouting -2
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): acquireWL(42416848): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1224 1027 null
D/PMS     (  902): releaseWL(42416848): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/PSReceiver( 3325): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1370): service - onCreate()
,I/ClockThread( 1104): stop update clock
V/NotificationService(  902): batLight: Full, plugged
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
I/SmartNS_PSService( 3325): onReceive:android.intent.action.USER_PRESENT
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3325):  defaultType:0
,D/AutoSetting( 1370): service - AddressCache: using context: com.htc.Weather
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,D/AutoSetting( 1370): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
,D/LocationManagerService(  902): request 423e9cd0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
,D/WifiNative-wlan0(  902):    returned false
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
,D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
D/NetworkPolicy(  902): updateScreenOn: false
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3779 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): acquireWL(425f67f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
D/PMS     (  902): releaseWL(425f67f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42350d10
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42350d10, eanble = 0, strlen(mName) = 91
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@4261fca8
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  902): goingToSleep
D/PMS     (  902): acquireWL(426daf80): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
I/FeedHostManager( 1238): [onPause]
,I/FeedProviderManager( 1238): onPause
I/FeedHostManager( 1238): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4200af70
I/SocialFeedProvider( 1238): +onPause
,I/SocialFeedProvider( 1238): -onPause
W/ContextImpl( 3779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=19639 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  902):    returned false
I/AlarmManager(  902): [AlarmQueuing] wifi connection: false
D/PMS     (  902): acquireWL(426fd438): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
D/PMS     (  902): releaseWL(426fd438): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  902): releaseWL(426daf80): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  902): updateScreenOn: false
,D/ContactMessageStore( 1214): start background delete task...
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete
,D/SmartSyncUtils( 3779): isEpsOn(), nState = 0
D/PMS     (  902): acquireWL(426cebd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3779 1000 null
,I/PhoneStatusBar( 1104): removeHeadsNotification.gc: 52
D/PMS     (  902): releaseWL(426cebd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3779): getMobilePolicyEnabled, result = true
,W/ContextImpl( 3779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 3779): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3779): getMobilePolicyEnabled, result = true
D/PMS     (  902): acquireWL(426e4478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
,D/PMS     (  902): releaseWL(426e4478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 3779): isEpsOn(), nState = 0
,D/AutoSetting( 1370): service - mHandler: cancel location update
,D/AutoSetting( 1370): service -           changes count: 0
D/WifiService(  902): New client listening to asynchronous messages
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4261fca8
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4261fca8, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4261fca8, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4261fca8
E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426201f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426201f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  902): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  902): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  902): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  902): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  902): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  902): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  902): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  902): killProcessQuiet, pid=3412
,I/ActivityManager(  902): Killing 3412:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 3412
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{4270f5f0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  902): acquireWL(426fa140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(426fa140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1370): service - handleMessage() stop self
,D/AutoSetting( 1370): service - onDestroy() END
,D/AutoSetting( 1370): service - handleMessage() quit looper
,D/Process (  902): killProcessQuiet, pid=3487
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3487:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3487
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(424e37e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10028}
,V/AlarmManager(  902): sending alarm PendingIntent{4238d2c8: PendingIntentRecord{425b4118 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140779, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{4231fc38: PendingIntentRecord{4210cf00 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141092, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{422548b0: PendingIntentRecord{42048748 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141097, Int=0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-,err=8
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/PMS     (  902): acquireWL(426e8738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(426e8738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  902): releaseWL(424e37e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  902): [NET] getaddrinfo-, 1
D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  902): [NET] getaddrinfo_proxy-
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(4269bde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4269bde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(426f04b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(426f04b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1214): switchBindHtcMsgCursor: null
,D/PMS     (  902): acquireWL(426f2340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(426f2340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-,err=8
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
D/PMS     (  902): acquireWL(426ca400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{422548b0: PendingIntentRecord{42048748 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201124, Int=0
D/PMS     (  902): releaseWL(426ca400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(425d4bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425d4bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(425d6e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425d6e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(425c0c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425c0c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(426ad528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(426ad528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(426b0a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(426b0a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/ContextImpl( 3779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
,D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3325): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3325): Index of the first 1 = -1
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3325): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3325): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(4272b4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4272b4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4272cdf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=329751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4272cdf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1544): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1544): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1343): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1343): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1343): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1343): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1343): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3593): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3593): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3593): [NET] getaddrinfo-,err=8
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3593): [NET] getaddrinfo-, 1
D/libc    ( 3593): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3593): [NET] getaddrinfo_proxy-
E/PlayEventLogger( 3593): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41bd28f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 2 10 3 12
,D/PMS     (  902): acquireWL(42726858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42726858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(425df258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425df258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(425e2818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425e2818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(425e4118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=449751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425e4118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(425e6398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425e6398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(427888e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=509751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427888e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(4278bdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4278bdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4278dca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=569751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4278dca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(427904d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427904d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1214): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1214): sku_id=99
D/ContactMessageStore( 1214): start background delete task...
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete
,D/PMS     (  902): acquireWL(42791dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=629751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42791dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1544): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1544): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1343): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1343): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1343): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1343): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1343): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3593): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3593): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41d01178 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3593): [NET] getaddrinfo-,err=8
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3593): [NET] getaddrinfo-, 1
,D/libc    ( 3593): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
I/RemoteViews.Performance( 1104): com.google.android.gms 2 15 5 12
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3593): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3593): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname),
,D/PMS     (  902): acquireWL(427d7610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427d7610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(427d8f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=689751, Int=0
,D/PMS     (  902): releaseWL(427d8f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(427db1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427db1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(427dcad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=749751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427dcad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(427dffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427dffa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(427e18a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=809751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427e18a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(427e3b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427e3b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(427e5428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=869751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427e5428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(427e8900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427e8900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(427ea220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=929751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427ea220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1544): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1544): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,W/GLSActivity( 1343): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1343): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1343): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1343): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1343): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41e9f818 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3593): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3593): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 18 5 12
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3593): [NET] getaddrinfo-,err=8
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3593): [NET] getaddrinfo-, 1
D/libc    ( 3593): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND),
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3593): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3593): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  902): acquireWL(4282f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4282f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(42831148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42831148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(428351d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,D/SmartSyncUtils( 3779): isEpsOn(), nState = 0
V/AlarmManager(  902): sending alarm PendingIntent{42393648: PendingIntentRecord{427593a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457093421030, Int=0
,D/PMS     (  902): acquireWL(428365e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3779 1000 null
,D/PMS     (  902): releaseWL(428351d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3779): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3779): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3779): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3779): SettingOnTime = 1457128800000, randomSettingOnTime = 1457127545000
,D/SmartSyncScreenOnOffTimeReceiver( 3779): SettingOffTime = 1457118000000, randomSettingOffTime = 1457118137000
D/SmartSyncScreenOnOffTimeReceiver( 3779): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3779): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3779): bNightModeTurnOffOnce = false
D/PMS     (  902): releaseWL(428365e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  902): acquireWL(42742440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42742440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(4272f7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4272f7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(426fce60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{41dfb448: PendingIntentRecord{4245e530 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780271, Int=0
,D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,I/ActivityManager(  902): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3824 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  902): sending alarm PendingIntent{423fb938: PendingIntentRecord{4250b2a0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457092630231, Int=10800000
,V/AlarmManager(  902): sending alarm PendingIntent{42403390: PendingIntentRecord{423bdac8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457093350843, Int=900000
W/ContextImpl( 3779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  902): sending alarm PendingIntent{4256f048: PendingIntentRecord{4253ce50 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457093499649, Int=1800000
,D/PowerUsageService( 3779): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3779): MY_DEBUG = false
D/PMS     (  902): acquireWL(426ed188): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1197 10028 null
,D/PMS     (  902): acquireWL(426aa028): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1197 10028 null
,D/PMS     (  902): releaseWL(426fce60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  902): releaseWL(426ed188): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1197): Aggregate from 1457091699602 (log), 1457091699602 (data)
W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.aurora (3824/10047)
,W/EventLogAggregator( 1197): Unknown tag: install_package_attempt
W/EventLogAggregator( 1197): Unknown tag: snet
,W/EventLogAggregator( 1197): Unknown tag: snet_gcore
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): releaseWL(426aa028): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/Process (  902): killProcessQuiet, pid=3525
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3525:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  902): Recipient 3525
,D/PMS     (  902): acquireWL(425bfea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425bfea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42662058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1109751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42662058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,D/PMS     (  902): acquireWL(4272a268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4272a268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(425bea80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1169751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425bea80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(425c1558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425c1558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  902): acquireWL(4268e698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1544): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1544): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(4268e698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(427d9580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c81908: PendingIntentRecord{41c40dd0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1229751, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427d9580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1197/10028)
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1544): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1544): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1343): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1343): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1343): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1343): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1343): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1343): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3593): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3593): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3593): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41f3a470 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3593): [NET] getaddrinfo-,err=8
D/libc    ( 3593): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3593): [NET] getaddrinfo-, 1
,D/libc    ( 3593): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3593): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3593): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1104): com.google.android.gms 2 11 4 12,
,D/PMS     (  902): acquireWL(427e5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427e5c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3844): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3844): ====startRecUseTime====
D/htc.customization.log.level( 3844):  is 
W/CustomizationLogLevel( 3844): Level value is invalid, use default level 2
D/CustomizationManager( 3844):  Read ACC file spent 0.127 (s)
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3844): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3844): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3844): Parsing tag category name = system
I/CustomizationCIDLoader( 3844): Parsing tag category name = application
I/CustomizationCIDLoader( 3844): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3844): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3844): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3844): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3844): Parsing tag category name = Settings
D/CustomizationManager( 3844):  Read CID file spent 0.178 (s)
D/CustomizationManager( 3844):  All configurations done spent 0.178 (s)
W/HtcNativeFlag( 3844): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3844): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3844): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3844): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  902): deletePackageAsUser: pkg=com.test.thalitest, pid=3844, uid=2000 user=0
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  902): Skipping PackageSetting{42204018 com.example.hello/10190} due to missing metadata
W/PackageSettings(  902): Skipping PackageSetting{42208520 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1238): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1238): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1544): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/acms    ( 1767): Unregistering com.test.thalitest
E/acms    ( 1767): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1544): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1544): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1415): Ignoring removeGeofence because network location is disabled.
D/PMS     (  902): acquireWL(428826a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1415 10028 null
D/PMS     (  902): releaseWL(428826a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/PackageManager(  902): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  902): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
D/VoicemailCleanupService( 1269): Cleaning up data for package: com.test.thalitest
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
W/SystemReader( 1224): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/PackageBroadcastService( 1197): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/ActivityManager(  902): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=3859 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
E/ExternalAccountType( 1311): Unsupported attribute readOnly
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/FileUtils(  902): Failed to chmod(/data/system/users/0/package-restrictions.xml): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/MultiDex( 3859): install
I/MultiDex( 3859): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 3859): loading existing secondary dex files
I/MultiDex( 3859): load found 1 secondary dex files
I/ActivityManager(  902): Delaying start of: ServiceRecord{426c96b8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 3859): install done
I/PeopleContactsSync( 1197): CP2 sync disabled
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1197, uid=10028, userID:0
D/PMS     (  902): acquireWL(4282e420): PARTIAL_WAKE_LOCK  Icing 0x1 1197 10028 null
I/Icing   ( 1197): doRemovePackageData com.test.thalitest
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1197): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1197): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1197): Writing status failed
D/PMS     (  902): releaseWL(4282e420): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 3859): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  902): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=3882 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  902): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 1197): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1197): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1197): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1197): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1197): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1197): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1197): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1197): Runtime exception while performing operation
E/ClearPendingStateOp( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1197): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1197): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1197): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1197): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1197): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1197): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 3882): install
I/MultiDex( 3882): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
F/ClearPendingStateOp( 1197): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1197): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1197): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1197): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1197): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1197): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1197): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 3882): loading existing secondary dex files
I/MultiDex( 3882): load found 1 secondary dex files
I/MultiDex( 3882): install done
I/ProviderInstaller( 3882): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/DropBoxManagerService(  902): Can't write: system_app_wtf
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
W/SQLiteConnectionPool( 1197): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1197): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1197): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 3280:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  902): killProcessQuiet, pid=3280
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SharedPreferencesImpl( 1179): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1370): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1370): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca69a10
W/[PluginManager]RegisterService( 1370): provider may killed!
W/[PluginManager]RegisterService( 1370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1370): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1370): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1370): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1370): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1370): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1370): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  902): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3280
I/[PluginManager]RegisterService( 1370): handle notify Blinkfeed plugin client changed
I/ActivityManager(  902): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1238): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 3859): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3859): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 3859): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 3859): 	at ctn.run(SourceFile:985)
W/dalvikvm( 3859): threadid=12: thread exiting with uncaught exception (group=0x41712e30)
E/AndroidRuntime( 3859): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3859): Process: com.google.android.gms.drive, PID: 3859
E/AndroidRuntime( 3859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3859): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 3859): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 3859): 	at ctn.run(SourceFile:985)
I/ActivityManager(  902): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/ActivityManager(  902): App crashed! Process: com.google.android.gms.drive
I/IcingCorporaProvider( 2642): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Process ( 3859): killProcess, pid=3859
D/Process ( 3859): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
E/SQLiteLog( 2642): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2642): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x643da5d0
W/dalvikvm( 2642): threadid=15: thread exiting with uncaught exception (group=0x41712e30)
E/AndroidRuntime( 2642): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2642): Process: com.google.android.googlequicksearchbox:search, PID: 2642
E/AndroidRuntime( 2642): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2642): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2642): 	at cid.d(PG:186)
E/AndroidRuntime( 2642): 	at clo.g(PG:594)
E/AndroidRuntime( 2642): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2642): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2642): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2642): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2642): 	at clr.tL(PG:827)
E/AndroidRuntime( 2642): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2642): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2642): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  902): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2642): killProcess, pid=2642
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
D/Process ( 2642): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  902): Recipient 3859
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.google.android.gms.drive (pid 3859) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Recipient 2642
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.google.android.googlequicksearchbox:search (pid 2642) has died.
D/MediaRouterService(  902): Client com.google.android.googlequicksearchbox (pid 2642): Died!
D/WifiService(  902): Client connection lost with reason: 4
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3904 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 1197): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1197): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1197): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1197): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1197): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1197): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1197): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1197): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1197): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1197): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1197): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1197): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1197): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1197): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1197): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1197): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1197): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1197): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1197): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1197): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1197): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1197): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1197): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1197): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1197): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1197): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1197): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 1197): threadid=10: thread exiting with uncaught exception (group=0x41712e30)
E/ActivityManager(  902): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1197): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1197): Process: com.google.android.gms, PID: 1197
E/AndroidRuntime( 1197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1197): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1197): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1197): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1197): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1197): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1197): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1197): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  902): Process com.google.android.gms has crashed too many times: killing!
D/Process (  902): killProcessQuiet, pid=1197
I/ActivityManager(  902): Killing 1197:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
I/Prism.ItemManager( 1238): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1238): loadItems() com.htc.launcher.pageview.WidgetManager@41bd4f70 +
I/Prism.WidgetManager( 1238): onLoadItems() +
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageManager(  902): Unable to load service info ResolveInfo{4249a070 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  902): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  902): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  902): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  902): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  902): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  902): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 3904): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3904): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3904): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3904): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3904): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3904): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3904): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3904): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3904): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3904): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3904): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3904): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3904): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3904): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3904): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3904): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3904): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3904): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3904): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3904): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3904): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3904): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3904): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3904): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3904): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3904): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3904): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3904): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3904): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3904): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3904): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3904): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3904): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3904): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3904): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3904): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3904): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3904): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3904): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3904): threadid=11: thread exiting with uncaught exception (group=0x41712e30)
E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 3904): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3904): Process: com.google.android.apps.docs, PID: 3904
E/AndroidRuntime( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3904): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3904): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3904): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3904): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3904): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
E/SQLiteDatabase( 3904): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3904): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3904): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3904): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3904): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3904): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3904): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3904): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3904): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3904): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 3904): killProcess, pid=3904
D/Process ( 3904): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 

```
