#### Test 613623660556c10_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
I/SensorManager(  904): mEventCount = 1050
E/cutils-trace( 3779): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3779): ====startRecUseTime====
D/htc.customization.log.level( 3779):  is 
W/CustomizationLogLevel( 3779): Level value is invalid, use default level 2
D/CustomizationManager( 3779):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3779): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3779): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3779): Parsing tag category name = system
I/CustomizationCIDLoader( 3779): Parsing tag category name = application
I/CustomizationCIDLoader( 3779): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3779): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3779): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3779): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3779): Parsing tag category name = Settings
D/CustomizationManager( 3779):  Read CID file spent 0.093 (s)
D/CustomizationManager( 3779):  All configurations done spent 0.093 (s)
W/HtcNativeFlag( 3779): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3779): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3779): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3779): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3779
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 12 times.
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1488): Don't start project servcice
,D/HtcModeClient( 1488): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1488): connectState: CONNECTION_READY = false
,D/SilentMusic( 1488): call stop
,D/HtcModeClient( 1488): close connection
,W/HtcModeClient( 1488): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1488): read the terminate packet, so break
,D/Process (  904): killProcessQuiet, pid=3500
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3500:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3500
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 1200
,D/PMS     (  904): acquireWL(425cdda8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(425cdda8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4238de08): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(4238de08): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(424fd2f8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(424fd2f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42452ee8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42452ee8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/SensorManager(  904): mEventCount = 1350
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3794 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(4251ff08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{42597488: PendingIntentRecord{4262d598 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456908899853, Int=60000
,D/PMS     (  904): releaseWL(4251ff08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3794): SMSBackupAgentService started
,D/SMSBackup( 3794): Checking restore status
,D/SMSBackup( 3794): Restore complete
,D/SMSBackup( 3794): cancelCheckAlarm
,D/SMSBackup( 3794): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3519
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3519:com.htc.updater/u0a84 (adj 15): empty #17
,D/PMS     (  904): acquireWL(426cf498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
I/ActivityManager(  904): Recipient 3519
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=103643, Int=0
,D/PMS     (  904): releaseWL(426cf498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1104): now=1456908900061 next=59939
,I/SensorManager(  904): mEventCount = 1500
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42130fe0
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,W/PMS     (  904): mWirelessDisplayManager is null
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42130fe0, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f70910
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@423554d8
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 415ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): OOBE c monitor 11
D/NfcService( 1228): ScreenObserver: OFF
,D/NfcService( 1228): applyRouting - 0
,D/NfcService( 1228): applyRouting -2
,I/IntentController( 1104): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426ef2f8)
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=1241
D/PMS     (  904): acquireWL(426ad180): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  904): releaseWL(426ad180): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  904): wakingUp
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
I/WindowManager(  904): No lock screen! windowToken=null
,D/PMN     (  904): onScreenOn
W/XT9_C   ( 1181): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1181): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2208): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/PMS     (  904): acquireWL(42705c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/MtpService( 2208): [MTP][onReceive]-
,D/NfcService( 1228): applyRouting - 0
D/NfcService( 1228): applyRouting -2
,D/AutoSetting( 1407): receiver - intent: android.intent.action.USER_PRESENT
I/BatteryService(  904): n_update end
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): releaseWL(42705c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): acquireWL(426c0cd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  904): releaseWL(426c0cd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1407): service - onCreate()
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3331): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3331): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3331): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3331): Cust_ConnectToPC   : spcsc>false
D/        ( 3331): Cust_ConnectToPC   : IPT>true
,D/        ( 3331): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3331): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3331): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3331): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3331): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1407): service - AddressCache: using context: com.htc.Weather
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/ClockThread( 1104): stop update clock
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/PSReceiver( 3331): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
W/ContextImpl( 3331): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  904): << updateStatus
D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  904):    returned false
I/SmartNS_PSService( 3331): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3331): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3331):  defaultType:0
,D/LocationManagerService(  904): request 425a7d00 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,V/SRS_Proc(  379): ParamSet string: screen_state=on
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  904): updateScreenOn: false
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/ContextImpl( 3733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): acquireWL(426053f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f70910
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f70910, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@423554d8
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  904): releaseWL(426053f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMN     (  904): goingToSleep
,D/PMS     (  904): acquireWL(4267dcc0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/SmartSyncUtils( 3733): isEpsOn(), nState = 0
,I/FeedHostManager( 1241): [onPause]
,I/FeedProviderManager( 1241): onPause
,I/FeedHostManager( 1241): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b45e38
I/SocialFeedProvider( 1241): +onPause
,I/SocialFeedProvider( 1241): -onPause
D/PMS     (  904): acquireWL(425c8970): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3733 1000 null
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19811 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  904):    returned false
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: false
D/PMS     (  904): acquireWL(42703410): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(42703410): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  379): ParamSet string: screen_state=off
D/PMS     (  904): releaseWL(4267dcc0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  904): releaseWL(425c8970): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/NetworkPolicy(  904): updateScreenOn: false
D/SmartSyncUtils( 3733): getMobilePolicyEnabled, result = true
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3733): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3733): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3733): getMobilePolicyEnabled, result = true
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423554d8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423554d8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423554d8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiService(  904): New client listening to asynchronous messages
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423554d8
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425a5760 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425a5760 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  904): acquireWL(426a55f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/AutoSetting( 1407): service - mHandler: cancel location update
,D/AutoSetting( 1407): service -           changes count: 0
D/PMS     (  904): releaseWL(426a55f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  904): acquireWL(425d2c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425d2c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4265d220 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(425efd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425efd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1407): service - handleMessage() stop self
,D/AutoSetting( 1407): service - handleMessage() quit looper
,D/AutoSetting( 1407): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=3417
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3417:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3417
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42712718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42371cd8: PendingIntentRecord{42566dd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140633, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{4244a9d0: PendingIntentRecord{424a13d0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141257, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{421f15f0: PendingIntentRecord{424580e0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141269, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-,
D/PMS     (  904): acquireWL(42720dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(42720dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  904): releaseWL(42712718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(426de370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426de370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  904): acquireWL(426e1938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426e1938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(425fe338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425fe338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(425ffbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-,err=8
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
V/AlarmManager(  904): sending alarm PendingIntent{421f15f0: PendingIntentRecord{424580e0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201290, Int=0
,D/PMS     (  904): releaseWL(425ffbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    (  904): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(42687928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42687928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42689b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42689b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(426cb5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=283643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426cb5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  904): acquireWL(426cea98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426cea98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(425d5900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425d5900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(425d77c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425d77c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NotificationStore( 1342): System rebooted after Notification storage file was last written
,I/NotificationStore( 1342): Deleting the file
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3622): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3622): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3622): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3622): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41bc0740 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 2 10 3 12
,D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3622): [NET] getaddrinfo-,err=8
D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3622): [NET] getaddrinfo-, 1
,D/libc    ( 3622): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3622): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3622): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(42702c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42702c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(42665520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=403643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42665520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42668ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42668ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4266a3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4266a3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(4278ae68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4278ae68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4278c768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=523643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4278c768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(4278fc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4278fc60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42791560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=583642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42791560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42768d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42768d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1217): sku_id=99
D/ContactMessageStore( 1217): start background delete task...
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/PMS     (  904): acquireWL(4276a640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=643642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4276a640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3622): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3622): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3622): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3622): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3622): [NET] getaddrinfo-,err=8
D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3622): [NET] getaddrinfo-, 1
,D/libc    ( 3622): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3622): [NET] getaddrinfo_proxy-
E/PlayEventLogger( 3622): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41cf4140 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 2 15 4 12
,D/PMS     (  904): acquireWL(427d71d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427d71d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3837 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  904): acquireWL(427d9a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10047}
,V/AlarmManager(  904): sending alarm PendingIntent{424e76d8: PendingIntentRecord{4251a8a0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1456909016891, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{42598f20: PendingIntentRecord{42435b98 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456909498620, Int=0
,D/PMS     (  904): releaseWL(427d9a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (3837/10047)
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3622): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3622): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3622): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3622): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3622): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/Process (  904): killProcessQuiet, pid=2534
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2534:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2534
,D/PMS     (  904): acquireWL(42811a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=703642, Int=0
,D/PMS     (  904): releaseWL(42811a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(428195e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{41f6fb38: PendingIntentRecord{42522f40 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456909513836, Int=0
,D/PMS     (  904): releaseWL(428195e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3622): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(428195e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428195e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(427e0ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=763643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427e0ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  904): acquireWL(427dd6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427dd6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42791ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=823643, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42791ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4271b510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4271b510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42708c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=883642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42708c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  904): acquireWL(426f3a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426f3a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(426efdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426efdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 3622): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3622): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3622): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3622): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3622): [NET] getaddrinfo-,err=8
D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3622): [NET] getaddrinfo-, 1
,D/libc    ( 3622): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3622): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3622): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41e45798 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 12 4 12
,D/PMS     (  904): acquireWL(426985c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426985c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42698430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42698430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(4267c4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41dd1828: PendingIntentRecord{42477328 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781525, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41b354b0: PendingIntentRecord{42452a58 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456909737303, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42469b48: PendingIntentRecord{4264c6d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456909806962, Int=0
,W/ContextImpl( 3733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PowerUsageService( 3733): call getInstance()
,D/SmartSyncUtils( 3733): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3733): MY_DEBUG = false
D/PMS     (  904): acquireWL(42560de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3733 1000 null
,D/PMS     (  904): releaseWL(4267c4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 3733): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3733): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3733): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3733): SettingOnTime = 1456984800000, randomSettingOnTime = 1456983363000
D/SmartSyncScreenOnOffTimeReceiver( 3733): SettingOffTime = 1456963200000, randomSettingOffTime = 1456968466000
D/SmartSyncScreenOnOffTimeReceiver( 3733): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3733): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3733): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(42560de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(428cd590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428cd590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(428cf458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1063642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428cf458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(428d16d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428d16d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(428d2fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1123642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428d2fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  904): acquireWL(428d64b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428d64b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(428d7db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1183642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428d7db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(428da030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(428da030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(428db930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42345e48: PendingIntentRecord{423440b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1243642, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428db930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1342): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1342): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1342): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1342): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1342): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1342): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41dddc98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3622): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3622): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3622): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3622): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3622): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 8 3 12
,D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3622): [NET] getaddrinfo-,err=8
D/libc    ( 3622): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3622): [NET] getaddrinfo-, 1
,D/libc    ( 3622): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3622): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3622): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(4286bfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4286bfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3858): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3858): ====startRecUseTime====
D/htc.customization.log.level( 3858):  is 
W/CustomizationLogLevel( 3858): Level value is invalid, use default level 2
D/CustomizationManager( 3858):  Read ACC file spent 0.092 (s)
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3858): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3858): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3858): Parsing tag category name = system
I/CustomizationCIDLoader( 3858): Parsing tag category name = application
I/CustomizationCIDLoader( 3858): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3858): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3858): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3858): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3858): Parsing tag category name = Settings
D/CustomizationManager( 3858):  Read CID file spent 0.143 (s)
D/CustomizationManager( 3858):  All configurations done spent 0.143 (s)
W/HtcNativeFlag( 3858): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3858): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3858): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3858): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=3858, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  904): Skipping PackageSetting{42298278 com.example.hello/10190} due to missing metadata
W/PackageSettings(  904): Skipping PackageSetting{4229b810 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/acms    ( 1770): Unregistering com.test.thalitest
D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
E/acms    ( 1770): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1420): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(425ff7a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/PMS     (  904): releaseWL(425ff7a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/PackageManager(  904): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  904): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
D/VoicemailCleanupService( 1269): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=3872 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
E/ExternalAccountType( 1303): Unsupported attribute readOnly
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/SQLiteDatabase( 1195): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1195): 	at fyb.d(SourceFile:96)
E/SQLiteDatabase( 1195): 	at fyb.a(SourceFile:220)
E/SQLiteDatabase( 1195): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteDatabase( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1195): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1195): 	at fyb.d(SourceFile:96)
E/SQLiteOpenHelper( 1195): 	at fyb.a(SourceFile:220)
E/SQLiteOpenHelper( 1195): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteOpenHelper( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1456910095352.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
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
I/MultiDex( 3872): install
W/SQLiteOpenHelper( 1195): Opened metrics.db in read-only mode
E/SQLiteLog( 1195): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
W/dalvikvm( 1195): threadid=31: thread exiting with uncaught exception (group=0x41705e30)
I/MultiDex( 3872): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  904): Delaying start of: ServiceRecord{425c8970 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/AndroidRuntime( 1195): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1195): Process: com.google.android.gms, PID: 1195
E/AndroidRuntime( 1195): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1195): 	at fyb.a(SourceFile:223)
E/AndroidRuntime( 1195): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/AndroidRuntime( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms
I/MultiDex( 3872): loading existing secondary dex files
I/MultiDex( 3872): load found 1 secondary dex files
I/PeopleContactsSync( 1195): CP2 sync disabled
I/MultiDex( 3872): install done
D/Process ( 1195): killProcess, pid=1195
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
D/PMS     (  904): acquireWL(424130d0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
I/Icing   ( 1195): doRemovePackageData com.test.thalitest
D/Process ( 1195): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 3872): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ActivityManager(  904): Recipient 1195
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms (pid 1195) has died.
D/PMS     (  904): handleWLDeath(424130d0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.games.service.GamesIntentService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=3897 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10979ms
I/MultiDex( 3897): install
I/MultiDex( 3897): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/SQLiteDatabase( 3872): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 3872): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3872): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 3872): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 3872): 	at ctn.run(SourceFile:985)
W/dalvikvm( 3872): threadid=12: thread exiting with uncaught exception (group=0x41705e30)
I/MultiDex( 3897): loading existing secondary dex files
I/MultiDex( 3897): load found 1 secondary dex files
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
I/MultiDex( 3897): install done
E/AndroidRuntime( 3872): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3872): Process: com.google.android.gms.drive, PID: 3872
E/AndroidRuntime( 3872): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3872): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 3872): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 3872): 	at ctn.run(SourceFile:985)
D/Process ( 3872): killProcess, pid=3872
D/Process ( 3872): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 3897): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Recipient 3872
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 3872) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20854ms
I/ActivityManager(  904): Resuming delayed broadcast
E/SharedPreferencesImpl( 1181): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1407): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1407): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1407): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca53128
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
I/[PluginManager]RegisterService( 1407): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1241): action: android.intent.action.PACKAGE_REMOVED
D/Process (  904): killProcessQuiet, pid=3578
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3578:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3578
I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3916 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2681): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2681): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63e9e468
W/dalvikvm( 2681): threadid=14: thread exiting with uncaught exception (group=0x41705e30)
E/AndroidRuntime( 2681): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2681): Process: com.google.android.googlequicksearchbox:search, PID: 2681
E/AndroidRuntime( 2681): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2681): 	at cid.d(PG:186)
E/AndroidRuntime( 2681): 	at clo.g(PG:594)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2681): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2681): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2681): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2681): 	at clr.tL(PG:827)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2681): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2681): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2681): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2681): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2681): killProcess, pid=2681
D/Process ( 2681): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  904): Recipient 2681
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2681) has died.
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2681): Died!
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 20618ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 30618ms
D/WifiService(  904): Client connection lost with reason: 4
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1241): loadItems() com.htc.launcher.pageview.WidgetManager@41bc7ed0 +
I/Prism.WidgetManager( 1241): onLoadItems() +
E/SQLiteDatabase( 3916): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3916): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3916): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3916): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3916): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3916): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3916): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3916): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3916): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3916): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3916): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3916): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3916): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3916): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3916): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3916): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3916): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3916): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3916): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3916): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3916): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3916): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3916): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3916): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3916): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3916): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3916): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3916): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3916): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3916): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3916): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3916): 	at dalvik.system.NativeStart.main(Native Method)
W/PackageManager(  904): Unable to load service info ResolveInfo{424b4108 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3916): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3916): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3916): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3916): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3916): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3916): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3916): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3916): threadid=11: thread exiting with uncaught exception (group=0x41705e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 3916): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3916): Process: com.google.android.apps.docs, PID: 3916
E/AndroidRuntime( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3916): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3916): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3916): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3916): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3916): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 3916): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3916): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3916): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3916): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3916): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3916): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3916): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3916): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3916): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3916): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3916): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3916): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3916): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3916): Opened ClientFlag.db in read-only mode
D/Process ( 3916): killProcess, pid=3916
D/Process ( 3916): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3932 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 3916
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 3916) has died.

```
