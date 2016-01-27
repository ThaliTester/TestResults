#### Test 564496604206eac_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/PMS     (  909): Going to sleep due to screen timeout...
--------- beginning of /dev/log/main
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a54a8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a54a8, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee8f8
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@423cfc48
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
E/cutils-trace( 3906): Error opening trace file: No such file or directory (2)
D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 310ms
W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43496348)
I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/NfcService( 1231): ScreenObserver: OFF
D/NfcService( 1231): applyRouting - 0
D/NfcService( 1231): applyRouting -2
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
D/PMN     (  909): onScreenOn
D/PMS     (  909): acquireWL(43dde120): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
D/PMS     (  909): releaseWL(43dde120): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  909): Disable input method client, pid=1249
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): acquireWL(42ab3a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(42ab3a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/NfcService( 1231): applyRouting - 0
D/MtpService( 2150): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2150): [MTP][onReceive]-
D/NfcService( 1231): applyRouting -2
D/AutoSetting( 1305): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PMS     (  909): acquireWL(42d3d4e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMS     (  909): releaseWL(42d3d4e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1305): service - onCreate()
D/TetherSettings( 3321): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3321): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3321): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3321): Cust_ConnectToPC   : spcsc>false
D/        ( 3321): Cust_ConnectToPC   : IPT>true
D/        ( 3321): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3321): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3321): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3321): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3321): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
I/PSReceiver( 3321): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1305): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  909):    returned false
I/SmartNS_PSService( 3321): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3321): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3321):  defaultType:0
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3321): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1305): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ClockThread( 1109): stop update clock
D/LocationManagerService(  909): request 423aefe0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  909): updateScreenOn: false
W/ActivityManager(  909): Disable JIT of com.htc.bgp
I/ActivityManager(  909): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3922 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/CustomizationManager( 3906): ====startRecUseTime====
D/htc.customization.log.level( 3906):  is 
W/CustomizationLogLevel( 3906): Level value is invalid, use default level 2
D/PMS     (  909): acquireWL(42d64560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42d64560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(436a0b90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/CalendarProvider2( 3922): Created com.android.providers.calendar.CalendarAlarmManager@41b24c50(com.android.providers.calendar.HtcCalendarProvider@41b0cfd8)
D/CalendarProvider2( 3922): wait start:true
D/PMS     (  909): releaseWL(436a0b90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee8f8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee8f8, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@423cfc48
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(4365ae38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cfea20
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=21052 mDataStallAlarmIntent=null
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  909):    returned false
D/CalendarProvider2( 3922): wait end:false
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: false
D/PMS     (  909): acquireWL(42d44388): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/PMS     (  909): releaseWL(42d44388): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  909): releaseWL(4365ae38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  909): updateScreenOn: false
D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
D/ContactMessageStore( 1220): Background delete complete
I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3941 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/CustomizationManager( 3906):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3906): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3906): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3906): Parsing tag category name = system
I/CustomizationCIDLoader( 3906): Parsing tag category name = application
I/CustomizationCIDLoader( 3906): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3906): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3906): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3906): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3906): Parsing tag category name = Settings
D/CustomizationManager( 3906):  Read CID file spent 0.103 (s)
D/CustomizationManager( 3906):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 3906): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3906): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3906): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3906): Fail to get flag for type 'language', use default value: -1
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  909): acquireWL(4351cad8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3906
D/PMS     (  909): acquireHCC(436d6b28): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(43975ae8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
D/PMS     (  909): releaseWL(4351cad8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/asset   (  909): Copying FileAsset 0x62bf25f0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1129320648
D/PMS     (  909): acquireWL(42d243e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3941 1000 null
D/PMS     (  909): releaseWL(42d243e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3962 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/PMS     (  909): acquireWL(437be560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(437be560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 3941): isEpsOn(), nState = 0
D/AutoSetting( 1305): service - mHandler: cancel location update
D/AutoSetting( 1305): service -           changes count: 0
D/SmartSyncUtils( 3941): getMobilePolicyEnabled, result = true
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
W/asset   ( 3962): Copying FileAsset 0x5c76b428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1249): [trimMemory] 20
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3941): isEpsOn(), nState = 0
D/SmartSyncUtils( 3941): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 3941): isEpsOn(), nState = 0
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423cfc48
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423cfc48, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423cfc48, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423cfc48
D/WifiService(  909): New client listening to asynchronous messages
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423d65a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423d65a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
V/WebViewChromiumFactoryProvider( 3962): Binding Chromium to main looper Looper (main, tid 1) {41aed750}
I/LibraryLoader( 3962): Expected native library version number "",actual native library version number ""
I/chromium( 3962): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3962): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(42d0f5f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425a55b8:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3962): 1102066120: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  909): acquireWL(434c6fa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  909): releaseWL(434c6fa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3962): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3962): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3962): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3962): Local Branch: 
I/Adreno-EGL( 3962): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3962): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3962):                  aa63bbd948f41d15fc72f585e
W/chromium( 3962): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3962): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3962): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3962): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3962): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3962): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3962): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3962): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3962): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3962): CordovaWebView is running on device made by: HTC
,W/ResourceType( 3962): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3962): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b34750, mServedView=org.apache.cordova.engine.SystemWebView{41afa4e0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,W/AwContents( 3962): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  909): Disable input method client, pid=1249
,W/IInputConnectionWrapper( 3962): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +250ms (total +291ms)
,D/JsMessageQueue( 3962): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3962): JniHelper::setJavaVM(0x415c2048), pthread_self() = 1663802776
,I/chromium( 3962): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/CalendarProvider2( 3922): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3922): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ProviderChangeReceiver( 3855): ---------------------------------------------------
,D/ProviderChangeReceiver( 3855): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3855): start to updateAlertNotification!
,W/ContextImpl( 3869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3855): No fired or scheduled alerts
D/HtcAlertUtils( 3855): -- cancelReminderNotification --
D/HtcAlertUtils( 3855): broadcastExistReminder!
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  909): killProcessQuiet, pid=3374
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3374:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3374
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  909): Client com.google.android.music (pid 3374): Died!
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 11.950MB for 42652-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 12.027MB for 95956-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 12.107MB for 143930-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 12.221MB for 215890-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 12.396MB for 323830-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 12.668MB for 485740-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 13.659MB for 1092904-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 14.591MB for 1639352-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 15.835MB for 2459024-byte allocation
,I/dalvikvm-heap( 3962): Grow heap (frag case) to 18.018MB for 3688532-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(436d6b28): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(43975ae8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3962): Initializing JXcore engine
,W/jxcore-log( 3962): JXcore engine is ready
,W/jxcore-log( 3962): Starting JXcore engine
,W/jxcore-log( 3962): Platform android
W/jxcore-log( 3962): 
,W/jxcore-log( 3962): Process ARCH arm
W/jxcore-log( 3962): 
,I/jxcore-log( 3962): JXcore Cordova bridge is ready!
I/jxcore-log( 3962): 
,W/jxcore-log( 3962): JXcore engine is started
,E/jxcore  ( 3962): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3962): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3962): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  909): killProcessQuiet, pid=3357
,I/ActivityManager(  909): Killing 3357:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
W/PluginManager( 3962): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,W/IInputConnectionWrapper( 3962): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  909): Disable input method client, pid=3962
,I/ActivityManager(  909): Recipient 3357
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(42d0f5f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Process (  909): killProcessQuiet, pid=3397
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3397:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3397
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{44225688 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(43c614c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(43c614c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(434c9c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42452300: PendingIntentRecord{4267bcb8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134635, Int=0
,D/PMS     (  909): releaseWL(434c9c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1305): service - handleMessage() stop self
,D/AutoSetting( 1305): service - handleMessage() quit looper
,D/AutoSetting( 1305): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=3562
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3562:com.google.android.talk/u0a111 (adj 15): empty #17
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  909): Recipient 3562
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42d44ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{434a55e0: PendingIntentRecord{426fd820 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122888, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{421d69f0: PendingIntentRecord{4213a648 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142491, Int=0
,D/PMS     (  909): acquireWL(43652d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  909): releaseWL(43652d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(43b148e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(42d44ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): releaseWL(43b148e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(437e4de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437e4de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442fbf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442fbf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(43ad9250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
,V/AlarmManager(  909): sending alarm PendingIntent{42393398: PendingIntentRecord{424542e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146096, Int=0
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  909): [NET] getaddrinfo_proxy-
V/AlarmManager(  909): sending alarm PendingIntent{438652d0: PendingIntentRecord{426fd820 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182645, Int=0
,D/PMS     (  909): releaseWL(43ad9250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4260f150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  909): releaseWL(4260f150): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43693c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43693c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(434aea00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(434aea00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(436c8c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42d29768: PendingIntentRecord{426fd820 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=212664, Int=0
,D/PMS     (  909): releaseWL(436c8c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43aeb298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  909): acquireWL(42e913d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43aeb298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42e913d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4431fa88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025092
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025163
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025166
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025169
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026335
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026345
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028990
,D/PMS     (  909): releaseWL(4431fa88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43a10ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025092
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025163
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025166
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025169
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026335
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026345
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028990
,D/PMS     (  909): acquireWL(436f5a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1199): Vacuum at: now=1453885620354 tag=VacuumService
,D/PMS     (  909): releaseWL(43a10ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(436f5a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434b48c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024963
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025092
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025163
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025166
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025169
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026335
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026345
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028990
,D/PMS     (  909): releaseWL(434b48c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(442c5a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1335/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024963
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025092
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025163
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025166
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025169
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026335
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360026345
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028990
,D/PMS     (  909): releaseWL(442c5a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43d782d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d782d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
D/PMS     (  909): acquireWL(442ab198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42393398: PendingIntentRecord{424542e8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=242654, Int=0
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    (  909): [NET] getaddrinfo_proxy-
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4022 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{425bda40: PendingIntentRecord{423d0618 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453885619273, Int=10800000
,D/PMS     (  909): releaseWL(442ab198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4022/10049)
,I/ActivityManager(  909): Killing 3755:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3755
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 3755
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43af50e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/BatteryService(  909): n_update end
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43af50e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43863058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=272635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43863058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(44138510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(44138510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(44308080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44308080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437420f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=332635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437420f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43526a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43526a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3621): [NET] getaddrinfo-,err=8
D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3621): [NET] getaddrinfo-, 1
D/libc    ( 3621): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3621): [NET] getaddrinfo_proxy-
,D/PMS     (  909): acquireWL(43ae2430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43ae2430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43e49020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=392635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43e49020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(43510c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43510c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(434b0be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434b0be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437a36e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=452635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437a36e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43ae1de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(43ae1de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(442ccfb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442ccfb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(42d6e010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=512635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d6e010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(438159e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(438159e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437bab20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=572635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437bab20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442ed8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442ed8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42b21328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42b21328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1220): sku_id=99
D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,D/PMS     (  909): acquireWL(43af03d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=632636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43af03d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  909): killProcessQuiet, pid=3785
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3785:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3785
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43a28250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a28250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3621): [NET] getaddrinfo-,err=8
D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3621): [NET] getaddrinfo-, 1
D/libc    ( 3621): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3621): [NET] getaddrinfo_proxy-
,D/PMS     (  909): acquireWL(435093e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(435093e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43ace910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=692636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ace910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43acb198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43acb198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442ce438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(442ce438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437c7398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=752636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437c7398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42a48770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42a48770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(429c89c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(429c89c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(436694a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=812635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(436694a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43af4db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43af4db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42684948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42684948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4364d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=872635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4364d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43ae9b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43ae9b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b2b2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43b2b2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4352ce50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=932635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4352ce50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3621): [NET] getaddrinfo-,err=8
D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3621): [NET] getaddrinfo-, 1
,D/libc    ( 3621): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3621): [NET] getaddrinfo_proxy-
,D/PMS     (  909): acquireWL(442aa018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442aa018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43d4d410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43d4d410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d3d2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  909): sending alarm PendingIntent{41d54d80: PendingIntentRecord{4247d630 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783265, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{423f9710: PendingIntentRecord{423f5620 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453886339588, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{42545ff0: PendingIntentRecord{42776b88 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453886412046, Int=0
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
D/PowerUsageService( 3941): call getInstance()
D/SmartSyncUtils( 3941): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3941): MY_DEBUG = false
D/PMS     (  909): releaseWL(43d3d2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): acquireWL(43ae14a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3941 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3941): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3941): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3941): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3941): SettingOnTime = 1453960800000, randomSettingOnTime = 1453959851000
,D/SmartSyncScreenOnOffTimeReceiver( 3941): SettingOffTime = 1453946400000, randomSettingOffTime = 1453949831000,
D/SmartSyncScreenOnOffTimeReceiver( 3941): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3941): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3941): bNightModeTurnOffOnce = false
,D/PMS     (  909): releaseWL(43ae14a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(43ae5bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43ae5bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42d306b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42d306b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42b1b9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1052636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42b1b9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d39c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d39c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442a0dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442a0dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4361ac88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1112635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4361ac88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(436f0148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(436f0148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(434c2108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434c2108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(44320f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1172636, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44320f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(434bead0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(434bead0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4426eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4426eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(436f1d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1232635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(436f1d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42aadbf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(42aadbf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3621): [NET] getaddrinfo-,err=8
D/libc    ( 3621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3621): [NET] getaddrinfo-, 1
,D/libc    ( 3621): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3621): [NET] getaddrinfo_proxy-
,D/PMS     (  909): acquireWL(434e4f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434e4f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42b13348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{421135f8: PendingIntentRecord{420e7df8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1292635, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42b13348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4078): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4078): ====startRecUseTime====
D/htc.customization.log.level( 4078):  is 
W/CustomizationLogLevel( 4078): Level value is invalid, use default level 2
D/CustomizationManager( 4078):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4078): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4078): Parsing tag category name = system
I/CustomizationCIDLoader( 4078): Parsing tag category name = application
I/CustomizationCIDLoader( 4078): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4078): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4078): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4078): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4078): Parsing tag category name = Settings
D/CustomizationManager( 4078):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4078):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4078): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4078): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4078, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=3962
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  909): Killing 3962:com.test.thalitest/u0a389 (adj 11): stop com.test.thalitest
W/asset   (  909): Copying FileAsset 0x69696f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  909): Skipping PackageSetting{42155fd8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(4431c598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4431c598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1275): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1249): Deferring update until onResume
D/Launcher( 1249): waitUntilResume // bindAppsRemoved
I/PackageManager(  909):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1305): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/[PluginManager]RegisterService( 1305): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Scheme: "mms"
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4092 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  909): acquireWL(43c8ab40): PARTIAL_WAKE_LOCK  Icing 0x1 1967 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43c8ab40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43af6428): PARTIAL_WAKE_LOCK  Icing 0x1 1967 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 295 ms] updated apps [took 295 ms] 
W/PackageManager(  909): Unable to load service info ResolveInfo{42da8f20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
W/GAV2    ( 4092): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4114 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
W/ContextImpl( 4114): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4114): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4114): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4114): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4114): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4114): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4114): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4114): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4114): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4114): threadid=10: thread exiting with uncaught exception (group=0x416bae30)
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/ActivityManager(  909): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4114): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4114): Process: com.android.keychain, PID: 4114
E/AndroidRuntime( 4114): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4114): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4114): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4114): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4114): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4114): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4114): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4114): killProcess, pid=4114
D/Process ( 4114): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453886723892.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 4114
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4114) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4129 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4129): getInstance(Context context)
D/AppTag  ( 4129): getInstance(Context context)
D/AppTag  ( 4129): onCreate()
I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  909): acquireWL(434cb8e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3600 10160 null
D/PMS     (  909): releaseWL(434cb8e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
W/dalvikvm( 3621): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1967): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1967): Clearing selected account for com.test.thalitest
I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/LocationSettingsChecker( 1967): Removing dialog suppression flag for package com.test.thalitest
W/GAV2    ( 4092): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/SQLiteDatabase( 1967): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1967): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1967): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1967): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1967): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1967): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1967): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1967): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1967): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1967): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1967): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1967): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1967): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1967): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1967): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1967): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1967): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1967): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1967): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1967): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1967): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1967): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1967): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1967): threadid=35: thread exiting with uncaught exception (group=0x416bae30)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1967): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1967): Process: com.google.android.gms, PID: 1967
E/AndroidRuntime( 1967): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1967): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1967): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1967): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1967): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1967): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1967): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1967): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1967): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1967): killProcess, pid=1967
D/Process ( 1967): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Recipient 1967
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): handleWLDeath(43af6428): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  909): Process com.google.android.gms (pid 1967) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
I/ActivityManager(  909): Resuming delayed broadcast
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b7cd38 +
I/Prism.WidgetManager( 1249): onLoadItems() +

```
