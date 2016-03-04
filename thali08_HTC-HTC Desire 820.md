#### Test 614329799926788_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  902): acquireWL(42594b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42594b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of /dev/log/main
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1104): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 3749): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3749): ====startRecUseTime====
D/htc.customization.log.level( 3749):  is 
W/CustomizationLogLevel( 3749): Level value is invalid, use default level 2
D/CustomizationManager( 3749):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3749): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3749): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3749): Parsing tag category name = system
I/CustomizationCIDLoader( 3749): Parsing tag category name = application
I/CustomizationCIDLoader( 3749): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3749): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3749): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3749): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3749): Parsing tag category name = Settings
D/CustomizationManager( 3749):  Read CID file spent 0.094 (s)
D/CustomizationManager( 3749):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 3749): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3749): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3749): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3749): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3749
D/Process (  902): killProcessQuiet, pid=3200
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3200:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
I/ActivityManager(  902): Recipient 3200
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 9 times.
,I/SensorManager(  902): mEventCount = 900
,D/PMS     (  902): acquireWL(423988c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10073}
,V/AlarmManager(  902): sending alarm PendingIntent{4238ec28: PendingIntentRecord{41e4bea0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457077193420, Int=0
,D/PMS     (  902): releaseWL(423988c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 10 times.
,D/AutoSetting( 1386): service - handleMessage() stop self
,D/AutoSetting( 1386): service - handleMessage() quit looper
,D/AutoSetting( 1386): service - onDestroy() END
,D/Process (  902): killProcessQuiet, pid=3446
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3446:com.htc.sdm/u0a80 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3446
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
D/PMS     (  902): acquireWL(41eda440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{4218b6f0: PendingIntentRecord{41bd8f50 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81451, Int=0
D/PMS     (  902): releaseWL(41eda440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1209): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1209): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  902): mEventCount = 1050
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 11 times.
,D/PMS     (  902): acquireWL(422a8470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=84134, Int=0
I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(422a8470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1104): now=1457077200060 next=59940
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 12 times.
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,I/SensorManager(  902): mEventCount = 1200
,D/PMS     (  902): acquireWL(420351f0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  902): releaseWL(420351f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(422a5528): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  902): releaseWL(422a5528): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42305c50): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  902): releaseWL(42305c50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(424096a8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  902): releaseWL(424096a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,V/LightsService(  902): setLight #2: color=#ff
,D/qdlights(  902): set_light_buttons_func: on=255 brightness=255
,E/qdlights(  902): write_int failed to open /sys/class/leds/button-backlight/brightness
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1472): Don't start project servcice
,D/HtcModeClient( 1472): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1472): connectState: CONNECTION_READY = false
D/SilentMusic( 1472): call stop
,D/HtcModeClient( 1472): close connection
,W/HtcModeClient( 1472): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1472): read the terminate packet, so break
,D/Process (  902): killProcessQuiet, pid=3475
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3475:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3475
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  902): Client connection lost with reason: 4
,I/SensorManager(  902): mEventCount = 1350
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3765 uid=10077 gids={50077}
D/PMS     (  902): acquireWL(4267c328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10077}
V/AlarmManager(  902): sending alarm PendingIntent{42251490: PendingIntentRecord{41e8c158 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457077219857, Int=60000
,D/PMS     (  902): releaseWL(4267c328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3765): SMSBackupAgentService started
,D/SMSBackup( 3765): Checking restore status
,D/SMSBackup( 3765): Restore complete
,D/SMSBackup( 3765): cancelCheckAlarm
,D/SMSBackup( 3765): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  902): killProcessQuiet, pid=2536
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2536:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 2536
,D/HABCtrl (  902): TPE algorithm. schedule timeout.
,D/HABCtrl (  902): ALG=2, lsvalue=225(4th)->160(3th), last_level=4, lValue=116->116
,D/HABCtrl (  902): mTPEAlgorithmTimeoutTask: TPE algorithm. restore.
,I/SensorManager(  902): mEventCount = 1500
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42126d00
,W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
W/PMS     (  902): mWirelessDisplayManager is null
,W/BatSI   (  902): Couldn't get kernel wake lock stats
D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  902): pid=902, uid=1000
,W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42126d00, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42255d50
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@424e6f28
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
V/LightsService(  902): setLight #0: color=#0
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 418ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  902): nativeSetInteractive:false
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
D/HABCtrl (  902): TPE algorithm. remove timeout.
D/PMS     (  902): OOBE c monitor 11
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1225): ScreenObserver: OFF
,D/NfcService( 1225): applyRouting - 0
,D/NfcService( 1225): applyRouting -2
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
I/InputMethodManagerService(  902): Disable input method client, pid=1241
,D/PMS     (  902): acquireWL(425f1a28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
,I/IntentController( 1104): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4239a3e0)
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
D/PMN     (  902): wakingUp
D/PMS     (  902): acquireWL(4260c1c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(425f1a28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  902): No lock screen! windowToken=null
D/PMS     (  902): releaseWL(4260c1c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/XT9_C   ( 1179): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1179): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMN     (  902): onScreenOn
,D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
,D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
D/MtpService( 2204): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2204): [MTP][onReceive]-
D/NfcService( 1225): applyRouting - 0
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
,D/NfcService( 1225): applyRouting -2
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
D/PMS     (  902): acquireWL(426bd650): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
D/PMS     (  902): releaseWL(426bd650): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
,I/ClockThread( 1104): stop update clock
,D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  902):    returned false
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3783 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  902): updateScreenOn: false
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): acquireWL(4265f998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/PMS     (  902): releaseWL(4265f998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42255d50
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42255d50, eanble = 0, strlen(mName) = 91
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@424e6f28
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  902): acquireWL(4251ec70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3783 1000 null
D/PMN     (  902): goingToSleep
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
I/FeedHostManager( 1241): [onPause]
,I/FeedProviderManager( 1241): onPause
,I/FeedHostManager( 1241): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d11cb0
I/SocialFeedProvider( 1241): +onPause
,I/SocialFeedProvider( 1241): -onPause
D/PMS     (  902): acquireWL(42617e58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=20085 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  902):    returned false
D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
I/AlarmManager(  902): [AlarmQueuing] wifi connection: false
D/PMS     (  902): acquireWL(4261ecf0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
D/PMS     (  902): releaseWL(4261ecf0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PMS     (  902): releaseWL(42617e58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  902): releaseWL(4251ec70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/NetworkPolicy(  902): updateScreenOn: false
,D/ContactMessageStore( 1209): start background delete task...
D/ContactMessageStore( 1209): size: 0 , 0
,D/ContactMessageStore( 1209): Background delete complete
,D/SmartSyncUtils( 3783): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1386): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3341): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3341): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3341): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3341): Cust_ConnectToPC   : spcsc>false
D/        ( 3341): Cust_ConnectToPC   : IPT>true
D/        ( 3341): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3341): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3341): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3341): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3341): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1386): service - onCreate()
,I/PSReceiver( 3341): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1386): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3341): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3341): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3341):  defaultType:0
,W/ContextImpl( 3341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  902): request 41f3b3e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/AutoSetting( 1386): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
,I/PhoneStatusBar( 1104): removeHeadsNotification.gc: 52
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3783): getMobilePolicyEnabled, result = true,
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  902): New client listening to asynchronous messages
I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424e6f28
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424e6f28, eanble = 0, strlen(mName) = 36
,W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] getTotalRam: 1873 Mb
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424e6f28, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424e6f28
E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424e7498 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424e7498 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  902): acquireWL(42519ab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
D/PMS     (  902): releaseWL(42519ab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/Process (  902): killProcessQuiet, pid=3428
,I/ActivityManager(  902): Killing 3428:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 3428
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1386): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1386): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1386): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{4266d680 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  902): acquireWL(4259eaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/BatteryService(  902): n_update end
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(4259eaf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(424851f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{4218b6f0: PendingIntentRecord{41bd8f50 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141457, Int=0
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
V/AlarmManager(  902): sending alarm PendingIntent{42264e18: PendingIntentRecord{422d5f88 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141492, Int=0
V/AlarmManager(  902): sending alarm PendingIntent{41d750c0: PendingIntentRecord{42519de8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141945, Int=0
,D/AutoSetting( 1386): service - handleMessage() stop self
,D/AutoSetting( 1386): service - handleMessage() quit looper
,D/AutoSetting( 1386): service - onDestroy() END
,D/Process (  902): killProcessQuiet, pid=3512
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3512:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3512
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  902): acquireWL(4266eea8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(4266eea8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  902): releaseWL(424851f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  902): acquireWL(4258f378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=144134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4258f378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(426235d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PowerUI ( 1104): closing low battery warning: level=100
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): releaseWL(426235d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1209): switchBindHtcMsgCursor: null
,D/PMS     (  902): acquireWL(42641878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42641878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(42675eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
V/AlarmManager(  902): sending alarm PendingIntent{4218b6f0: PendingIntentRecord{41bd8f50 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201962, Int=0
D/PMS     (  902): releaseWL(42675eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(42653240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42653240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(426d1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(426d1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(4261b958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/PMS     (  902): releaseWL(4261b958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(4267f9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=264135, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4267f9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(425008a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425008a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(42501d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  902): n_update end
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(42501d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42611168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=324134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42611168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  902): acquireWL(42656ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(42656ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3605): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3605): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3605): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3605): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41ae8400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3605): [NET] getaddrinfo-,err=8
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3605): [NET] getaddrinfo-, 1
,D/libc    ( 3605): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
I/RemoteViews.Performance( 1104): com.google.android.gms 1 9 3 12
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3605): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3605): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  902): acquireWL(4265dd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(4265dd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(42644e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384135, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42644e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(4263b018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  902): releaseWL(4263b018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(425db498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(425db498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(425bdfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=444134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425bdfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  902): acquireWL(425c08d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(425c08d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(425c7678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/PMS     (  902): releaseWL(425c7678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(425ce800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=504134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425ce800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(425d1db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PMS     (  902): releaseWL(425d1db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(426d9490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(426d9490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(426e0618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=564134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(426e0618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(426e2978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(426e2978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(426e3e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(426e3e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1209): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1209): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1209): sku_id=99
D/ContactMessageStore( 1209): start background delete task...
,D/ContactMessageStore( 1209): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1209): size: 0 , 0
,D/ContactMessageStore( 1209): Background delete complete,
,D/PMS     (  902): acquireWL(426e5690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=624135, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(426e5690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(426e8c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(426e8c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,E/PlayEventLogger( 3605): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3605): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3605): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3605): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41ae2d30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3605): [NET] getaddrinfo-,err=8
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3605): [NET] getaddrinfo-, 1
,D/libc    ( 3605): [NET] getaddrinfo_proxy+
I/RemoteViews.Performance( 1104): com.google.android.gms 1 12 3 12
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3605): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3605): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname),
,D/PMS     (  902): acquireWL(42732148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(42732148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
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
,D/PMS     (  902): acquireWL(42739240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=684134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(42739240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4273b5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(4273b5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42742340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(42742340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(427494c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=744134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(427494c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(4274ca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(4274ca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42753820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42753820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4275a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=804134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4275a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4275cd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): releaseWL(4275cd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42763aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(42763aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4276ac30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=864135, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4276ac30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(4276e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,D/PowerUI ( 1104): closing low battery warning: level=100
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): releaseWL(4276e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42774f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(42774f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1104): closing low battery warning: level=100
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null,
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(4277c110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=924134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4277c110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4277e470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4277e470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3605): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3605): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3605): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3605): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3605): [NET] getaddrinfo-,err=8
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3605): [NET] getaddrinfo-, 1
,D/libc    ( 3605): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3605): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3605): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1104): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41f30060 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 2 15 5 12
,D/PMS     (  902): acquireWL(425f7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(425f7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): closing low battery warning: level=100
,D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(424dd250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(424dd250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(424d2048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,D/SmartSyncUtils( 3783): isEpsOn(), nState = 0
V/AlarmManager(  902): sending alarm PendingIntent{41cecf98: PendingIntentRecord{4247fb38 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457078127786, Int=0
D/PMS     (  902): acquireWL(424b5af0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3783 1000 null
D/PMS     (  902): releaseWL(424d2048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3783): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3783): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3783): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 23
W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,I/FeedHostManager( 1241): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,D/SmartSyncScreenOnOffTimeReceiver( 3783): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3783): SettingOnTime = 1457128800000, randomSettingOnTime = 1457126703000
,D/SmartSyncScreenOnOffTimeReceiver( 3783): SettingOffTime = 1457118000000, randomSettingOffTime = 1457118752000
,D/PMS     (  902): acquireWL(42449690): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1241 10075 null
I/FeedHostManager( 1241): NightMode begin at 0, end at 7
D/SmartSyncScreenOnOffTimeReceiver( 3783): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3783): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 3783): bNightModeTurnOffOnce = false
,D/PMS     (  902): releaseWL(424b5af0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  902): acquireWL(42446ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  902): sending alarm PendingIntent{41d24f70: PendingIntentRecord{4238e1e8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780865, Int=0
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,I/ActivityManager(  902): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=3847 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  902): sending alarm PendingIntent{424a9e90: PendingIntentRecord{42296a38 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1457077336416, Int=10800000
,D/PMS     (  902): releaseWL(42446ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/FeedHostManager( 1241): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1457078127958, BeginTime: 1457132400000, EndTime: 1457157600000
D/PMS     (  902): releaseWL(42449690): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.aurora (3847/10047)
,D/Process (  902): killProcessQuiet, pid=3529
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3529:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3529
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(41cec5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(41cec5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1104): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(41f3e3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(41f3e3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(424c9ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1044135, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(424c9ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(423559a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(423559a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  902): acquireWL(424b8090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1104134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(424b8090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(422b93d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  902): n_update end
D/PowerUI ( 1104): closing low battery warning: level=100
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): releaseWL(422b93d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(423408b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1164134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(423408b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(4260ab90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{4246efa8: PendingIntentRecord{424fc090 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457078056768, Int=900000
,V/AlarmManager(  902): sending alarm PendingIntent{41f96b30: PendingIntentRecord{424c77b0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457078280118, Int=1800000
,W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3783): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3783): MY_DEBUG = false
D/PMS     (  902): acquireWL(4230a900): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1195 10028 null
D/PMS     (  902): releaseWL(4260ab90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,I/EventLogService( 1195): Aggregate from 1457076480046 (log), 1457076480046 (data)
D/PMS     (  902): acquireWL(423ffca0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1195 10028 null
D/PMS     (  902): releaseWL(4230a900): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/EventLogAggregator( 1195): Unknown tag: install_package_attempt
W/EventLogAggregator( 1195): Unknown tag: snet
,W/EventLogAggregator( 1195): Unknown tag: snet_gcore
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): releaseWL(423ffca0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,D/PMS     (  902): acquireWL(426c8c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-,
D/PMS     (  902): releaseWL(426c8c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus,
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  902): acquireWL(42753dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PMS     (  902): releaseWL(42753dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  902): acquireWL(4264cf88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1224134, Int=0
,I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4264cf88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/PMS     (  902): acquireWL(427444f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427444f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
E/PlayEventLogger( 3605): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3605): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3605): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3605): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1104): com.google.android.gms (false,0)
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3605): [NET] getaddrinfo-,err=8
D/libc    ( 3605): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3605): [NET] getaddrinfo-, 1
D/libc    ( 3605): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: ,
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND),
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3605): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3605): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1104): release indeterminate drawable android.widget.OnDemandProgressBar{41f8ba20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1104): com.google.android.gms 1 16 5 12
,D/PMS     (  902): acquireWL(426e0d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1104): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  902): releaseWL(426e0d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1104): closing low battery warning: level=100
D/PowerUI ( 1104): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1104): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 3871): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3871): ====startRecUseTime====
D/htc.customization.log.level( 3871):  is 
W/CustomizationLogLevel( 3871): Level value is invalid, use default level 2
D/CustomizationManager( 3871):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3871): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3871): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3871): Parsing tag category name = system
I/CustomizationCIDLoader( 3871): Parsing tag category name = application
I/CustomizationCIDLoader( 3871): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3871): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3871): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3871): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3871): Parsing tag category name = Settings
D/CustomizationManager( 3871):  Read CID file spent 0.160 (s)
D/CustomizationManager( 3871):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 3871): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3871): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3871): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3871): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  902): deletePackageAsUser: pkg=com.test.thalitest, pid=3871, uid=2000 user=0
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  902): Skipping PackageSetting{4216ccc8 com.example.hello/10190} due to missing metadata
W/PackageSettings(  902): Skipping PackageSetting{4216fd48 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  902): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1104): ApplicationsIntentReceiver replacing:false
I/acms    ( 1768): Unregistering com.test.thalitest
E/acms    ( 1768): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  902): acquireWL(4283e9d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1401 10028 null
W/GeofencerStateMachine( 1401): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1296): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1296): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  902): releaseWL(4283e9d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  902): acquireWL(42841588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{41c38ef0: PendingIntentRecord{41d490a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1284134, Int=0
D/VoicemailCleanupService( 1254): Cleaning up data for package: com.test.thalitest
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
W/PackageManager(  902): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  902): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1296): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/ActivityManager(  902): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=3885 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
E/ExternalAccountType( 1296): Unsupported attribute readOnly
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/ActivityManager(  902): Delaying start of: ServiceRecord{4269b708 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/MultiDex( 3885): install
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1209 :
D/PhoneApp( 1209): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 3885): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 1195): CP2 sync disabled
I/MultiDex( 3885): loading existing secondary dex files
I/MultiDex( 3885): load found 1 secondary dex files
I/MultiDex( 3885): install done
I/Icing   ( 1195): doRemovePackageData com.test.thalitest
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
D/PMS     (  902): acquireWL(424b8a78): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  902): releaseWL(424b8a78): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  902): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=3907 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 3885): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  902): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 3907): install
I/MultiDex( 3907): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/SQLiteDatabase( 1195): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
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
E/SQLiteDatabase( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1195): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1195): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1195): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1195): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1195): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1195): Runtime exception while performing operation
E/ClearPendingStateOp( 1195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1195): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1195): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1195): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1195): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1195): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 3907): loading existing secondary dex files
F/ClearPendingStateOp( 1195): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1195): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1195): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1195): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1195): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1195): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1195): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1195): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1195): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 3907): load found 1 secondary dex files
I/MultiDex( 3907): install done
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
I/ProviderInstaller( 3907): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  902): Resuming delayed broadcast
D/Process (  902): killProcessQuiet, pid=3296
I/ActivityManager(  902): Killing 3296:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SharedPreferencesImpl( 1179): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1386): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1386): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1386): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9aea60
W/[PluginManager]RegisterService( 1386): provider may killed!
W/[PluginManager]RegisterService( 1386): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1386): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1386): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1386): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1386): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1386): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1386): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1386): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1386): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  902): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1386): handle notify Blinkfeed plugin client changed
I/ActivityManager(  902): Resuming delayed broadcast
E/SQLiteDatabase( 3885): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 3885): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3885): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3885): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3885): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 3885): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 3885): 	at ctn.run(SourceFile:985)
W/dalvikvm( 3885): threadid=12: thread exiting with uncaught exception (group=0x4165fe30)
E/ActivityManager(  902): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 3885): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3885): Process: com.google.android.gms.drive, PID: 3885
E/AndroidRuntime( 3885): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3885): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3885): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3885): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 3885): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 3885): 	at ctn.run(SourceFile:985)
D/Prism.PackageStateRece_( 1241): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 3885): killProcess, pid=3885
D/Process ( 3885): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  902): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  902): Recipient 3885
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  902): Process com.google.android.gms.drive (pid 3885) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3928 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  902): Recipient 3296
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 2653): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2653): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca1a160
W/dalvikvm( 2653): threadid=14: thread exiting with uncaught exception (group=0x4165fe30)
E/AndroidRuntime( 2653): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2653): Process: com.google.android.googlequicksearchbox:search, PID: 2653
E/AndroidRuntime( 2653): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2653): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2653): 	at cid.d(PG:186)
E/AndroidRuntime( 2653): 	at clo.g(PG:594)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2653): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2653): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2653): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2653): 	at clr.tL(PG:827)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2653): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2653): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2653): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2653): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2653): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  902): App crashed! Process: com.google.android.googlequicksearchbox:search
W/PackageManager(  902): Unable to load service info ResolveInfo{42524b18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Process ( 2653): killProcess, pid=2653
D/Process ( 2653): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/ActivityManager(  902): Recipient 2653
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Process com.google.android.googlequicksearchbox:search (pid 2653) has died.
D/MediaRouterService(  902): Client com.google.android.googlequicksearchbox (pid 2653): Died!
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/WifiService(  902): Client connection lost with reason: 4
E/SQLiteDatabase( 1195): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
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
E/SQLiteDatabase( 1195): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1195): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1195): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1195): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1195): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1195): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1195): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1195): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1195): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1195): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1195): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1195): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1195): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1195): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1195): Couldn't open games_3a3529a.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 1195): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1195): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1195): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1195): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1195): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1195): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1195): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1195): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1195): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1195): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1195): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1195): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1195): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1195): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1195): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 1195): threadid=10: thread exiting with uncaught exception (group=0x4165fe30)
E/ActivityManager(  902): App crashed! Process: com.google.android.gms
D/Process (  902): killProcessQuiet, pid=1195
E/AndroidRuntime( 1195): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1195): Process: com.google.android.gms, PID: 1195
E/AndroidRuntime( 1195): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1195): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1195): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1195): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1195): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1195): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1195): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1195): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1195): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  902): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  902): Killing 1195:com.google.android.gms/u0a28 (adj 6): crash
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
D/RemoteDisplayProvider(  902): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
I/IntentController( 1104): receive(android.intent.action.TIME_TICK,1,false)
D/RemoteDisplayProvider(  902): start
D/PMS     (  902): releaseWL(42841588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/AtomicFile(  902): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  902): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 3928): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3928): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3928): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 3928): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 3928): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 3928): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 3928): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 3928): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 3928): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 3928): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 3928): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 3928): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 3928): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 3928): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3928): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3928): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3928): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3928): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 3928): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 3928): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 3928): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 3928): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 3928): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 3928): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 3928): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 3928): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 3928): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 3928): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 3928): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3928): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3928): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 3928): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3928): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 3928): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 3928): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 3928): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 3928): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 3928): threadid=11: thread exiting with uncaught exception (group=0x4165fe30)
E/AndroidRuntime( 3928): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 3928): Process: com.google.android.apps.docs, PID: 3928
E/AndroidRuntime( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3928): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 3928): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 3928): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 3928): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 3928): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
E/SQLiteDatabase( 3928): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3928): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 3928): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 3928): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3928): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 3928): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 3928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3928): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 3928): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 3928): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 3928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3928): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 3928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 3928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 3928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 3928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 3928): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 3928): Opened ClientFlag.db in read-only mode
D/Process ( 3928): killProcess, pid=3928
D/Process ( 3928): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3947 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  902): Recipient 3928
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  902): killProcessQuiet, pid=3640
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3640:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  902): Process com.google.android.apps.docs (pid 3928) has died.
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3640
W/ContextImpl( 3947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 

```
