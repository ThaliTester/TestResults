#### Test 5667282762e056f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
I/PMS     (  905): Going to sleep due to screen timeout...
--------- beginning of /dev/log/main
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421b53f8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421b53f8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a9920
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42a6c098
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  905): mWirelessDisplayManager is null
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
W/BatSI   (  905): Couldn't get kernel wake lock stats
D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 319ms
W/PnPMgr  (  353): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@442ed048)
D/NfcService( 1235): ScreenObserver: OFF
D/NfcService( 1235): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=1247
D/PMN     (  905): wakingUp
I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
E/cutils-trace( 3891): Error opening trace file: No such file or directory (2)
D/NfcService( 1235): applyRouting -2
V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(43659520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
D/PMS     (  905): releaseWL(43659520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): acquireWL(43752fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
W/ActivityManager(  905): Disable JIT of com.htc.bgp
D/PMS     (  905): releaseWL(43752fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiNative-wlan0(  905):    returned false
D/MtpService( 2209): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3903 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/NfcService( 1235): applyRouting - 0
D/MtpService( 2209): [MTP][onReceive]-
D/NfcService( 1235): applyRouting -2
I/ClockThread( 1109): stop update clock
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): acquireWL(42611118): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
D/PMS     (  905): releaseWL(42611118): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  905): updateScreenOn: false
I/SensorManager(  905): mEventCount = 900
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
I/CalendarProvider2( 3903): Created com.android.providers.calendar.CalendarAlarmManager@41b51d38(com.android.providers.calendar.HtcCalendarProvider@41b3a0c0)
D/CalendarProvider2( 3903): wait start:true
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43d2b130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43d2b130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43863f88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43863f88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/CalendarProvider2( 3903): wait end:false
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a9920
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420a9920, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42a6c098
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/CustomizationManager( 3891): ====startRecUseTime====
D/htc.customization.log.level( 3891):  is 
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(42967fd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
W/CustomizationLogLevel( 3891): Level value is invalid, use default level 2
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d80d68
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3924 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20349 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  905):    returned false
I/AlarmManager(  905): [AlarmQueuing] wifi connection: false
D/PMS     (  905): acquireWL(43b8b1c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(43b8b1c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  905): releaseWL(42967fd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  905): updateScreenOn: false
D/CustomizationManager( 3891):  Read ACC file spent 0.077 (s)
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3891): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3891): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3891): Parsing tag category name = system
I/CustomizationCIDLoader( 3891): Parsing tag category name = application
I/CustomizationCIDLoader( 3891): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3891): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3891): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3891): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3891): Parsing tag category name = Settings
D/CustomizationManager( 3891):  Read CID file spent 0.119 (s)
D/CustomizationManager( 3891):  All configurations done spent 0.119 (s)
W/HtcNativeFlag( 3891): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3891): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3891): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3891): Fail to get flag for type 'language', use default value: -1
D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
D/ContactMessageStore( 1218): Background delete complete
W/ContextImpl( 3924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3891
D/PMS     (  905): acquireHCC(441e6a18): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
I/PhoneStatusBar( 1109): removeHeadsNotification.gc: 56
D/PMS     (  905): acquireHCC(425d2528): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1138545480
D/PMS     (  905): acquireWL(420f8108): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3924 1000 null
D/PMS     (  905): releaseWL(420f8108): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3943 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/SmartSyncUtils( 3924): isEpsOn(), nState = 0
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): acquireWL(44323160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(44323160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(436a9e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(436a9e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 3924): getMobilePolicyEnabled, result = true
I/TrimMemoryManager( 1247): [trimMemory] 20
D/Process (  905): killProcessQuiet, pid=3618
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Killing 3618:com.google.android.talk/u0a111 (adj 15): empty #17
D/AutoSetting( 1290): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2875): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2875): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2875): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2875): Cust_ConnectToPC   : spcsc>false
D/        ( 2875): Cust_ConnectToPC   : IPT>true
D/        ( 2875): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2875): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2875): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2875): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2875): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1290): service - onCreate()
D/AutoSetting( 1290): service - AddressCache: using context: com.htc.Weather
I/PSReceiver( 2875): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1290): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/ContextImpl( 2875): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  905): request 4241ee10 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
I/SmartNS_PSService( 2875): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2875): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2875):  defaultType:0
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
V/WebViewChromiumFactoryProvider( 3943): Binding Chromium to main looper Looper (main, tid 1) {41b19658}
I/LibraryLoader( 3943): Expected native library version number "",actual native library version number ""
I/chromium( 3943): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3943): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3943): 1102250496: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b95fa8:true
D/PMS     (  905): acquireWL(43761828): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(437f07e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(43761828): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/SmartSyncUtils( 3924): isEpsOn(), nState = 0
I/Adreno-EGL( 3943): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3943): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3943): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3943): Local Branch: 
I/Adreno-EGL( 3943): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3943): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3943):                  aa63bbd948f41d15fc72f585e
D/SmartSyncUtils( 3924): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 3924): isEpsOn(), nState = 0
W/ContextImpl( 3924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a6c098
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a6c098, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a6c098, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a6c098
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42876030 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42876030 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3618
W/chromium( 3943): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3943): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3943): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3943): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3943): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3943): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3943): CordovaWebView is running on device made by: HTC
,I/InputMethodManagerService(  905): Disable input method client, pid=1247
W/ResourceType( 3943): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3943): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b61788, mServedView=org.apache.cordova.engine.SystemWebView{41b27518 VFEDH.C. .F....ID 0,0-720,1134 #64}
W/AwContents( 3943): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3943): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +286ms (total +321ms)
,D/JsMessageQueue( 3943): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3943): JniHelper::setJavaVM(0x415f0048), pthread_self() = 1663144632
,I/chromium( 3943): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/CalendarProvider2( 3903): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3903): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ProviderChangeReceiver( 3840): ---------------------------------------------------
,D/ProviderChangeReceiver( 3840): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3840): start to updateAlertNotification!
W/ContextImpl( 3855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3840): No fired or scheduled alerts
,D/HtcAlertUtils( 3840): -- cancelReminderNotification --
,D/HtcAlertUtils( 3840): broadcastExistReminder!
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 11.951MB for 42652-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 12.038MB for 95956-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 12.119MB for 143930-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 12.232MB for 215890-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 12.405MB for 323830-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 12.669MB for 485740-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 13.672MB for 1092904-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 14.588MB for 1639352-byte allocation
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 15.834MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(441e6a18): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(425d2528): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3943): Grow heap (frag case) to 18.018MB for 3688532-byte allocation
,W/jxcore-log( 3943): Initializing JXcore engine
,W/jxcore-log( 3943): JXcore engine is ready
,W/jxcore-log( 3943): Starting JXcore engine
,W/jxcore-log( 3943): Platform android
W/jxcore-log( 3943): 
,W/jxcore-log( 3943): Process ARCH arm
W/jxcore-log( 3943): 
,I/jxcore-log( 3943): JXcore Cordova bridge is ready!
I/jxcore-log( 3943): 
,W/jxcore-log( 3943): JXcore engine is started
,E/jxcore  ( 3943): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3943): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3943): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  905): killProcessQuiet, pid=3711,
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 3711:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3711
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/IInputConnectionWrapper( 3943): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  905): Disable input method client, pid=3943
,D/PMS     (  905): releaseWL(437f07e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Process (  905): killProcessQuiet, pid=3383
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3383:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3383
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1290): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1290): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1290): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42fa13b8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  905): acquireWL(44357c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(44357c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(438c1cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42db6af8: PendingIntentRecord{442cbd38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=130180, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4226bb80: PendingIntentRecord{4210fbe8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141919, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42416478: PendingIntentRecord{42486748 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141923, Int=0
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
V/AlarmManager(  905): sending alarm PendingIntent{423a3ec8: PendingIntentRecord{43a7dd58 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142755, Int=0
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  905): [NET] getaddrinfo_proxy-
D/PMS     (  905): acquireWL(430abe68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  905): releaseWL(430abe68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1290): service - handleMessage() stop self
,D/AutoSetting( 1290): service - handleMessage() quit looper
,D/AutoSetting( 1290): service - onDestroy() END
D/Process (  905): killProcessQuiet, pid=3744
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3744:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(438e25c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(438e25c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  905): releaseWL(438c1cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Recipient 3744
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(43669718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=153610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43669718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(44216638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(44216638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,I/ClearcutLoggerApiImpl( 1343): disconnect managed GoogleApiClient
,D/PMS     (  905): acquireWL(4394ae80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4394ae80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42a6bfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{44343720: PendingIntentRecord{442cbd38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189907, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4226bb80: PendingIntentRecord{4210fbe8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202774, Int=0
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/PMS     (  905): acquireWL(4250c4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42a6bfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    (  905): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(43dc4750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4250c4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43dc4750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4436cac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024282
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024285
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024289
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025565
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025577
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028209
,D/PMS     (  905): releaseWL(4436cac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42845e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023889
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024282
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024285
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024289
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025565
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025577
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028209
,D/PMS     (  905): acquireWL(441ec820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1200): Vacuum at: now=1453831069404 tag=VacuumService
D/PMS     (  905): releaseWL(42845e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441ec820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4389f128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024282
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024285
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024289
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024291
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025565
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025577
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028209
,D/PMS     (  905): releaseWL(4389f128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44372668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023889
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024282
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024285
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024289
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024291
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025565
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025577
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028209
,D/PMS     (  905): releaseWL(44372668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428403c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=213609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(428403c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(429a28d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429a28d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43d08cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(43d08cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(42d86458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=273610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d86458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(442be970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(442be970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44241360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=333609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44241360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=3765
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3765:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3765
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3540): [NET] getaddrinfo-,err=8
D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3540): [NET] getaddrinfo-, 1
,D/libc    ( 3540): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3540): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(44343308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(44343308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4423fb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=393609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4423fb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(44235d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(44235d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43d780b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d780b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43d74580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=453609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d74580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43d5a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(43d5a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43abcab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): releaseWL(43abcab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4380e7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=513610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4380e7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43804408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43804408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(437e1070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437e1070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43770270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=573609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43770270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4376f760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4376f760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4376e0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4376e0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1218): sku_id=99
,D/ContactMessageStore( 1218): start background delete task...
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/PMS     (  905): acquireWL(4376df00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=633610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4376df00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4376cc58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4376cc58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3540): [NET] getaddrinfo-,err=8
D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3540): [NET] getaddrinfo-, 1
,D/libc    ( 3540): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3540): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(424928d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424928d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4244de68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=693609, Int=0
,D/PMS     (  905): releaseWL(4244de68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4207f4e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PMS     (  905): releaseWL(4207f4e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42536c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42536c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4243b248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=753610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4243b248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42218cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(42218cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42476b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=813610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42476b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(422cc340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(422cc340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(41f04de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(41f04de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4243a398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=873609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4243a398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41e74c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PMS     (  905): releaseWL(41e74c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42437170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42437170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e18ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=933609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e18ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3540): [NET] getaddrinfo-,err=8
,D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3540): [NET] getaddrinfo-, 1
,D/libc    ( 3540): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3540): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(42426188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(42426188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e41cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=993609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e41cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/PMS     (  905): acquireWL(4283e6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d497c8: PendingIntentRecord{424abb80 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=789909, Int=0
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4034 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{420753b8: PendingIntentRecord{41f55540 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453831080041, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{42637c48: PendingIntentRecord{425f2928 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453831801214, Int=900000
V/AlarmManager(  905): sending alarm PendingIntent{42415f40: PendingIntentRecord{42db54e0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453831879199, Int=0
,W/ContextImpl( 3924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3924): call getInstance()
,D/SmartSyncUtils( 3924): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3924): MY_DEBUG = false
,D/PMS     (  905): acquireWL(42ddb788): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3924 1000 null
,D/PMS     (  905): releaseWL(4283e6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 3924): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3924): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3924): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3924): SettingOnTime = 1453874400000, randomSettingOnTime = 1453873792000
,D/SmartSyncScreenOnOffTimeReceiver( 3924): SettingOffTime = 1453860000000, randomSettingOffTime = 1453862182000
,D/SmartSyncScreenOnOffTimeReceiver( 3924): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3924): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3924): bNightModeTurnOffOnce = false
W/BatSI   (  905): Couldn't get kernel wake lock stats
D/PMS     (  905): releaseWL(42ddb788): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4034/10049)
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=3731
,I/ActivityManager(  905): Killing 3731:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3731
,D/PMS     (  905): acquireWL(4262d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4262d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d7b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(43d7b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44347790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1053610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44347790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43d41ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43d41ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43859370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43859370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43e3e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1113609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e3e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c34910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42c34910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e43648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e43648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42e24fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1173609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e24fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43d13da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d13da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(43017778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1233609, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43017778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436d83d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436d83d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3540): [NET] getaddrinfo-,err=8
D/libc    ( 3540): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3540): [NET] getaddrinfo-, 1
,D/libc    ( 3540): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3540): [NET] getaddrinfo_proxy-
,D/PMS     (  905): acquireWL(445e7600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(445e7600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(442d2340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42313aa8: PendingIntentRecord{42312658 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1293610, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(442d2340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4425b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4425b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4060): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4060): ====startRecUseTime====
D/htc.customization.log.level( 4060):  is 
W/CustomizationLogLevel( 4060): Level value is invalid, use default level 2
D/CustomizationManager( 4060):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4060): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4060): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4060): Parsing tag category name = system
I/CustomizationCIDLoader( 4060): Parsing tag category name = application
I/CustomizationCIDLoader( 4060): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4060): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4060): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4060): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4060): Parsing tag category name = Settings
D/CustomizationManager( 4060):  Read CID file spent 0.094 (s)
D/CustomizationManager( 4060):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4060): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4060): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4060): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4060): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4060, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=3943
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 3943:com.test.thalitest/u0a389 (adj 11): stop com.test.thalitest
W/PackageSettings(  905): Skipping PackageSetting{422e4e48 com.example.hello/10397} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(436df048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1315): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(436df048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1262): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1290): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/[PluginManager]RegisterService( 1290): handle notify Blinkfeed plugin client changed
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
W/AccTypeManager( 1315): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1315): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/IcingCorporaProvider( 2584): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
E/ExternalAccountType( 1315): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4075 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(43ec5aa0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2584): UpdateCorporaTask done [took 277 ms] updated apps [took 277 ms] 
W/PackageManager(  905): Unable to load service info ResolveInfo{42484748 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
W/GAV2    ( 4075): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/SQLiteLog( 4075): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
E/SQLiteDBG( 4075): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5ca3b968
E/AbstractDatabaseInstance( 4075): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4075): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4075): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4075): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4075): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4075): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4075): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4075): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4075): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4075): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4075): 	at fv.run(DocsApplication.java:288)
W/dalvikvm( 4075): threadid=11: thread exiting with uncaught exception (group=0x416e8e30)
E/AndroidRuntime( 4075): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4075): Process: com.google.android.apps.docs, PID: 4075
E/AndroidRuntime( 4075): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4075): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4075): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4075): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4075): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4075): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4075): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4075): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4075): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4075): 	at fv.run(DocsApplication.java:288)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
D/Process ( 4075): killProcess, pid=4075
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4098 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4075): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
I/ActivityManager(  905): Recipient 4075
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4075) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4098): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4098): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4098): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4098): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4098): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4098): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4098): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4098): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4098): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4098): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4098): threadid=10: thread exiting with uncaught exception (group=0x416e8e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4098): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4098): Process: com.android.keychain, PID: 4098
E/AndroidRuntime( 4098): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4098): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4098): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4098): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4098): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4098): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4098): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4098): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4098): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4098): killProcess, pid=4098
D/Process ( 4098): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453832190812.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4098
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4098) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10938ms
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4113 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4113): getInstance(Context context)
D/AppTag  ( 4113): getInstance(Context context)
D/AppTag  ( 4113): onCreate()
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(43d04160): PARTIAL_WAKE_LOCK  AsyncService 0x1 3511 10160 null
D/PMS     (  905): releaseWL(43d04160): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
W/dalvikvm( 3540): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1966): Clearing selected account for com.test.thalitest
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/LocationSettingsChecker( 1966): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteDatabase( 1966): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1966): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1966): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1966): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1966): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1966): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1966): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1966): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1966): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1966): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1966): threadid=37: thread exiting with uncaught exception (group=0x416e8e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process ( 1966): killProcess, pid=1966
D/Process ( 1966): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 1966): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1966): Process: com.google.android.gms, PID: 1966
E/AndroidRuntime( 1966): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1966): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1966): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 1966
I/ActivityManager(  905): Process com.google.android.gms (pid 1966) has died.
D/PMS     (  905): handleWLDeath(43ec5aa0): PARTIAL_WAKE_LOCK  Icing 0x1
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10580ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20580ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30580ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30580ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30579ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30579ms
I/ActivityManager(  905): Resuming delayed broadcast
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41baae10 +
I/Prism.WidgetManager( 1247): onLoadItems() +

```
