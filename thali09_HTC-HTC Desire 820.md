#### Test 573480784751f5c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  912): mEventCount = 900
,E/cutils-trace( 3881): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3881): ====startRecUseTime====
D/htc.customization.log.level( 3881):  is 
W/CustomizationLogLevel( 3881): Level value is invalid, use default level 2
D/CustomizationManager( 3881):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3881): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3881): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3881): Parsing tag category name = system
I/CustomizationCIDLoader( 3881): Parsing tag category name = application
I/CustomizationCIDLoader( 3881): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3881): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3881): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3881): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3881): Parsing tag category name = Settings
D/CustomizationManager( 3881):  Read CID file spent 0.111 (s)
D/CustomizationManager( 3881):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 3881): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3881): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3881): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3881): Fail to get flag for type 'language', use default value: -1
I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@427c1f58
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@427c1f58, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427f9ea8
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@42878ff8
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
--------- beginning of /dev/log/system
I/PMS     (  912): Going to sleep due to screen timeout...
W/PMS     (  912): mWirelessDisplayManager is null
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
W/CpuWake (  912): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  912): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3881
D/PMS     (  912): acquireHCC(44be3440): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 912 1000 null
D/PMS     (  912): acquireHCC(42cdbcd0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 912 1000 null
W/asset   (  912): Copying FileAsset 0x62aef5e0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  912): @test_code: getHtcIntentFlag: 0 obj: 1139811648
D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 347ms
D/PMS     (  912): nativeSetInteractive:false
D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
D/PMS     (  912): acquireWL(42c3c228): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
D/HABCtrl (  912): TPE algorithm. remove timeout.
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42273e88
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/NfcService( 1233): ScreenObserver: OFF
D/NfcService( 1233): applyRouting - 0
D/NfcService( 1233): applyRouting -2
I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
I/InputMethodManagerService(  912): Disable input method client, pid=1250
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
D/PMS     (  912): OOBE c monitor 11
D/PMS     (  912): acquireWL(436b8238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
D/PMS     (  912): acquireWL(438c22c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
D/PMS     (  912): releaseWL(436b8238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): releaseWL(438c22c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/ActivityManager(  912): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3894 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/InputMethodManagerService(  912): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@42a27b48 (uid=10076 pid=1250), inputType=0x0
V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43692978)
V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
D/PMN     (  912): wakingUp
I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/MtpService( 2143): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NfcService( 1233): applyRouting - 0
I/WindowManager(  912): No lock screen! windowToken=null
D/PMN     (  912): onScreenOn
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/MtpService( 2143): [MTP][onReceive]-
D/AutoSetting( 1300): receiver - intent: android.intent.action.USER_PRESENT
I/TrimMemoryManager( 1250): [trimMemory] 20
D/NfcService( 1233): applyRouting -2
D/TetherSettings( 2893): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2893): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2893): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2893): Cust_ConnectToPC   : spcsc>false
D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/asset   ( 3894): Copying FileAsset 0x5c873430 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/        ( 2893): Cust_ConnectToPC   : IPT>true
D/        ( 2893): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2893): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2893): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2893): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2893): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PMS     (  912): acquireWL(43b8a378): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
D/PMS     (  912): releaseWL(43b8a378): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
D/AutoSetting( 1300): service - onCreate()
I/PSReceiver( 2893): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 2893): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1300): service - AddressCache: using context: com.htc.Weather
W/Settings( 2893): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2893):  defaultType:0
W/ContextImpl( 2893): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  912): request 4288fee8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1300): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/ClockThread( 1110): stop update clock
V/WebViewChromiumFactoryProvider( 3894): Binding Chromium to main looper Looper (main, tid 1) {421143c0}
I/LibraryLoader( 3894): Expected native library version number "",actual native library version number ""
I/chromium( 3894): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3894): Initializing chromium process, renderers=0
I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
W/ActivityManager(  912): Disable JIT of com.htc.bgp
D/PMS     (  912): acquireWL(43924f28): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): acquireWL(4409fc50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): releaseWL(4409fc50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
W/System.err(  912): java.lang.Throwable: stack dump
D/WifiNative-wlan0(  912):    returned false
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4211bdb0:true
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3894): 1108524696: getState() :  mService = null. Returning STATE_OFF
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ActivityManager(  912): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=3913 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/Adreno-EGL( 3894): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3894): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3894): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3894): Local Branch: 
I/Adreno-EGL( 3894): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3894): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3894):                  aa63bbd948f41d15fc72f585e
D/NetworkPolicy(  912): updateScreenOn: false
W/Adreno-GSL( 3894): <gsl_ldd_control:412>: ioctl fd 69 code 0xc0140938 (unknown) failed: errno 22 Invalid argument
E/Adreno-ES20( 3894): <rb_cmdbuffer_issue:2401>: Failed to synchronously read for EXT_disjoint_timer_query
W/chromium( 3894): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/PMS     (  912): acquireWL(4371cae8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  912): releaseWL(4371cae8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/CalendarProvider2( 3913): Created com.android.providers.calendar.CalendarAlarmManager@42150d28(com.android.providers.calendar.HtcCalendarProvider@421390b0)
W/dalvikvm( 3894): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3894): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/PMS     (  912): acquireWL(44697520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(44697520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427f9ea8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427f9ea8, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@42878ff8
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/dalvikvm( 3894): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3894): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3894): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/CalendarProvider2( 3913): wait start:true
W/dalvikvm( 3894): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3894): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3894): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/PMN     (  912): goingToSleep
D/SystemWebViewEngine( 3894): CordovaWebView is running on device made by: HTC
D/PMS     (  912): acquireWL(436baaf0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
D/PMS     (  912): releaseWL(42c3c228): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/AlarmManager(  912): ACTION_SCREEN_OFF
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
I/AlarmManager(  912): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20088 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  912):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  912): acquireWL(42c38c60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
D/PMS     (  912): releaseWL(42c38c60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  912): updateScreenOn: false
,D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
,D/ContactMessageStore( 1219): Background delete complete
,D/CalendarProvider2( 3913): wait end:false
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3953 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  912): acquireWL(44bb3808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
D/PMS     (  912): releaseWL(44bb3808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(44ba8bf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(44ba8bf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1300): service - mHandler: cancel location update
,D/AutoSetting( 1300): service -           changes count: 0
W/ContextImpl( 3953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3953): isEpsOn(), nState = 0
D/PMS     (  912): acquireWL(44b9aef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3953 1000 null
D/PMS     (  912): releaseWL(436baaf0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/InputMethodManagerService(  912): Disable input method client, pid=1250
W/ResourceType( 3894): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3894): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4215d4a0, mServedView=org.apache.cordova.engine.SystemWebView{421231b0 VFEDH.C. .F....ID 0,0-720,1134 #64}
W/AwContents( 3894): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1188): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1188): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  912): releaseWL(44b9aef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3953): getMobilePolicyEnabled, result = true
,W/IInputConnectionWrapper( 3894): reportFullscreenMode on inactive InputConnection
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 3953): isEpsOn(), nState = 0
D/SmartSyncUtils( 3953): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3953): getMobilePolicyEnabled, result = true
I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42878ff8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42878ff8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
D/WifiService(  912): New client listening to asynchronous messages
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42878ff8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42878ff8
E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422ba808 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422ba808 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
,D/JsMessageQueue( 3894): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3894): JniHelper::setJavaVM(0x41cd5010), pthread_self() = 1663398048
,I/chromium( 3894): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 11.998MB for 42652-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 12.086MB for 95956-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 12.155MB for 143930-byte allocation
,I/CalendarProvider2( 3913): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 3913): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3831): ---------------------------------------------------
,D/ProviderChangeReceiver( 3831): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3831): start to updateAlertNotification!
W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3831): No fired or scheduled alerts
,D/HtcAlertUtils( 3831): -- cancelReminderNotification --
,D/HtcAlertUtils( 3831): broadcastExistReminder!
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  912): killProcessQuiet, pid=3691
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Killing 3691:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/dalvikvm-heap( 3894): Grow heap (frag case) to 12.269MB for 215890-byte allocation
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
,I/ActivityManager(  912): Recipient 3691
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 12.444MB for 323830-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 12.716MB for 485740-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 13.692MB for 1092904-byte allocation
,W/CpuWake (  912): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  912): <<release mCpuPerf_Freq wakelock
D/PMS     (  912): releaseHCC(44be3440): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  912): releaseHCC(42cdbcd0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 14.638MB for 1639352-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 15.882MB for 2459024-byte allocation
,I/dalvikvm-heap( 3894): Grow heap (frag case) to 18.075MB for 3688532-byte allocation
,W/jxcore-log( 3894): Initializing JXcore engine
,W/jxcore-log( 3894): JXcore engine is ready
,W/jxcore-log( 3894): Starting JXcore engine
,W/jxcore-log( 3894): Platform android
W/jxcore-log( 3894): 
,W/jxcore-log( 3894): Process ARCH arm
W/jxcore-log( 3894): 
,I/jxcore-log( 3894): JXcore Cordova bridge is ready!
I/jxcore-log( 3894): 
,W/jxcore-log( 3894): JXcore engine is started
,E/jxcore  ( 3894): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3894): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3894): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  912): killProcessQuiet, pid=3344
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  912): Killing 3344:com.htc.mediamanager/u0a34 (adj 15): empty #17
W/PluginManager( 3894): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3344
,D/PMS     (  912): releaseWL(43924f28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/IInputConnectionWrapper( 3894): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  912): Disable input method client, pid=3894
,D/Process (  912): killProcessQuiet, pid=3385
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3385:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3385
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{4371b3c8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  912): acquireWL(4379ef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4379ef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(437949d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(437949d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(42c75fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{42bfb310: PendingIntentRecord{42eef120 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137222, Int=0
,D/PMS     (  912): releaseWL(42c75fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1300): service - handleMessage() stop self
,D/AutoSetting( 1300): service - handleMessage() quit looper
,D/AutoSetting( 1300): service - onDestroy() END
,D/Process (  912): killProcessQuiet, pid=3607
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  912): Killing 3607:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3607
,D/PMS     (  912): acquireWL(429779f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{42463448: PendingIntentRecord{42cf9c18 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123477, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{42862130: PendingIntentRecord{423eb820 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141550, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{426670c8: PendingIntentRecord{42a46940 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141554, Int=0
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/PMS     (  912): acquireWL(42557cd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  912): [NET] getaddrinfo_proxy-
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,D/PMS     (  912): releaseWL(42557cd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(42a945d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(429779f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  912): releaseWL(42a945d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  912): acquireWL(4256a1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4256a1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
,D/PMS     (  912): acquireWL(42cd86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42cd86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42ab3458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): releaseWL(42ab3458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(428e0cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{4211bda0: PendingIntentRecord{42cf9c18 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182705, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{42862130: PendingIntentRecord{423eb820 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201576, Int=0
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-,err=8
D/PMS     (  912): acquireWL(42be2ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  912): [NET] getaddrinfo_proxy-
D/PMS     (  912): releaseWL(428e0cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,D/PMS     (  912): acquireWL(42b0deb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42be2ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42b0deb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42b30230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(42b30230): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42bfc808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): acquireWL(42af95c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PerfProfileCollectorService( 1964): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1964): removeStateFiles() called
,D/PerfProfileCollectorService( 1964): User is not opt-in to Usage & Diagnostics.
D/PMS     (  912): releaseWL(42af95c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(429aa258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42bfc808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1201): Vacuum at: now=1453985655031 tag=VacuumService
D/PMS     (  912): acquireWL(439a1650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(439a1650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(437862b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(437862b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(429aa258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42cc0410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(42cc0410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(44c7ad08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(44c7ad08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42be0c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1350/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023776
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024033
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025359
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360027872
,D/PMS     (  912): releaseWL(42be0c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4377ebe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(4377ebe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(42f18710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42f18710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43809430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43809430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(4300a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): releaseWL(4300a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(42a1e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42a1e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(437b2350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(437b2350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
D/PowerUI ( 1110): closing low battery warning: level=100
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c97e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c97e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3537): [NET] getaddrinfo-,err=8
D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3537): [NET] getaddrinfo-, 1
,D/libc    ( 3537): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3537): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(44a60000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(44a60000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4384b368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(4384b368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(436b8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=426957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(436b8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(44244cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(44244cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42a4e838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42a4e838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(442446f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(442446f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c2e228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c2e228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(43f3d568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=546957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43f3d568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4379d6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): releaseWL(4379d6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(442e2648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(442e2648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(443d7df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=606957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(443d7df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c08d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c08d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1219): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1219): sku_id=99
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
,D/ContactMessageStore( 1219): Background delete complete
,I/ActivityManager(  912): Killing 3725:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=3725
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3725
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(444c7b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): releaseWL(444c7b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3537): [NET] getaddrinfo-,err=8
D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3537): [NET] getaddrinfo-, 1
,D/libc    ( 3537): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3537): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(42c58f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=666957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c58f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4399a8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/PMS     (  912): releaseWL(4399a8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c6d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c6d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  912): updateBatteryInfo
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43324e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=726957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.698MB for 50416-byte allocation
D/PMS     (  912): releaseWL(43324e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43741980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43741980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43f12688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43f12688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(444d19f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=786957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(444d19f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(44b7d240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(44b7d240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43439348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(43439348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(439a3be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=846957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(439a3be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43115d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43115d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(4442d5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=906957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.698MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(4442d5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42ae3270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(42ae3270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42e76808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(42e76808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3537): [NET] getaddrinfo-,err=8
D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3537): [NET] getaddrinfo-, 1
,D/libc    ( 3537): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3537): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(42e75868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=966957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42e75868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43f9d138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(43f9d138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43993328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  912): sending alarm PendingIntent{422b7580: PendingIntentRecord{42aa9e60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785618, Int=0
,D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4028 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{42c41980: PendingIntentRecord{42bb3ae0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453985663649, Int=10800000
,V/AlarmManager(  912): sending alarm PendingIntent{4288dd68: PendingIntentRecord{42b68ab0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453986383913, Int=900000
,V/AlarmManager(  912): sending alarm PendingIntent{42b2cc30: PendingIntentRecord{42b32008 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453986460405, Int=0
,W/ContextImpl( 3953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3953): call getInstance()
,D/SmartSyncUtils( 3953): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3953): MY_DEBUG = false
D/PMS     (  912): releaseWL(43993328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  912): acquireWL(438474f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3953 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 3953): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 3953): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 3953): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3953): SettingOnTime = 1454047200000, randomSettingOnTime = 1454043717000
,D/SmartSyncScreenOnOffTimeReceiver( 3953): SettingOffTime = 1454032800000, randomSettingOffTime = 1454035491000
,D/SmartSyncScreenOnOffTimeReceiver( 3953): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3953): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3953): bNightModeTurnOffOnce = false
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/PMS     (  912): releaseWL(438474f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (4028/10049)
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,I/ActivityManager(  912): Killing 3756:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=3756
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3756
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(440dfa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(440dfa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43855438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1026957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43855438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(437d4b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(437d4b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  912): updateBatteryInfo
,D/PowerUI ( 1110): closing low battery warning: level=100
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(433a17e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1086957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(433a17e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(432285c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(432285c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42cf78a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(42cf78a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42bbebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1146957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42bbebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42b1f548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42b1f548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(429c2388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1206957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(429c2388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42949930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(42949930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3537): [NET] getaddrinfo-,err=8
D/libc    ( 3537): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3537): [NET] getaddrinfo-, 1
D/libc    ( 3537): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3537): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(42ab7e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42a285a0: PendingIntentRecord{429fd2a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1266957, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42ab7e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42a31350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42a31350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(4299a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(4299a590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4052): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4052): ====startRecUseTime====
D/htc.customization.log.level( 4052):  is 
W/CustomizationLogLevel( 4052): Level value is invalid, use default level 2
D/CustomizationManager( 4052):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4052): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4052): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4052): Parsing tag category name = system
I/CustomizationCIDLoader( 4052): Parsing tag category name = application
I/CustomizationCIDLoader( 4052): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4052): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4052): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4052): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4052): Parsing tag category name = Settings
D/CustomizationManager( 4052):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4052):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4052): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4052): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4052): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4052): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  912): deletePackageAsUser: pkg=com.test.thalitest, pid=4052, uid=2000 user=0
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  912): killProcessQuiet, pid=3894
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  912): Killing 3894:com.test.thalitest/u0a389 (adj 11): stop com.test.thalitest
W/asset   (  912): Copying FileAsset 0x6be82d30 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  912): Skipping PackageSetting{42797f60 com.example.hello/10397} due to missing metadata
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  912): acquireWL(42d08fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42d08fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1262): Cleaning up data for package: com.test.thalitest
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1300): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/InputMethodManagerService(  912): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/[PluginManager]RegisterService( 1300): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/IcingCorporaProvider( 2584): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/ActivityManager(  912): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4066 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  912): acquireWL(444cfe48): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2584): UpdateCorporaTask done [took 275 ms] updated apps [took 275 ms] 
W/PackageManager(  912): Unable to load service info ResolveInfo{42a4c4b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4066): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4066): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4066): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4066): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4066): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4066): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4066): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4066): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4066): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4066): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4066): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4066): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4066): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4066): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4066): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4066): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4066): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4066): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4066): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4066): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4066): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4066): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4066): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4066): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4066): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4066): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4066): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4066): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4066): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4066): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4066): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4066): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4066): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4066): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4066): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4066): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4066): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4066): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4066): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4066): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4066): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4066): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4066): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4066): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4066): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4066): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4066): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4066): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4066): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4066): threadid=11: thread exiting with uncaught exception (group=0x41ce6e30)
E/ActivityManager(  912): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4066): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4066): Process: com.google.android.apps.docs, PID: 4066
E/AndroidRuntime( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4066): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4066): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4066): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4066): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4066): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4066): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4066): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4066): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4066): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4066): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4066): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4066): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4066): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4066): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4066): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4066): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4066): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4066): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4066): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4066): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4066): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4066): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4066): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4066): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4066): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4066): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4066): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4066): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4066): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4066): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4066): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4066): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4066): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4066): Opened ClientFlag.db in read-only mode
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
D/Process ( 4066): killProcess, pid=4066
D/Process ( 4066): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  912): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4085 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  912): Recipient 4066
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  912): start
I/ActivityManager(  912): Process com.google.android.apps.docs (pid 4066) has died.
W/AtomicFile(  912): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  912): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4085): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4085): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4085): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4085): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4085): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4085): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4085): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4085): threadid=10: thread exiting with uncaught exception (group=0x41ce6e30)
I/ActivityManager(  912): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4098 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  912): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4085): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4085): Process: com.android.keychain, PID: 4085
E/AndroidRuntime( 4085): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4085): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4085): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4085): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4085): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4085): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4085): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4085): killProcess, pid=4085
D/Process ( 4085): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453986771610.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
I/ActivityManager(  912): Recipient 4085
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.android.keychain (pid 4085) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4098): getInstance(Context context)
D/AppTag  ( 4098): getInstance(Context context)
D/AppTag  ( 4098): onCreate()
D/PMS     (  912): acquireWL(429b78e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3510 10160 null
D/PMS     (  912): releaseWL(429b78e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3537): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1964): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1964): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
I/ActivityManager(  912): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1964): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1964): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1964): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6577f330
W/dalvikvm( 1964): threadid=34: thread exiting with uncaught exception (group=0x41ce6e30)
E/AndroidRuntime( 1964): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1964): Process: com.google.android.gms, PID: 1964
E/AndroidRuntime( 1964): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1964): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1964): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1964): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1964): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1964): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1964): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1964): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1964): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1964): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1964): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1964): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1964): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  912): App crashed! Process: com.google.android.gms
D/Process ( 1964): killProcess, pid=1964
D/Process ( 1964): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Recipient 1964
I/ActivityManager(  912): Process com.google.android.gms (pid 1964) has died.
D/PMS     (  912): handleWLDeath(444cfe48): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30999ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30999ms
I/ActivityManager(  912): Resuming delayed broadcast
E/SQLiteLog( 1350): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1350): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63ffc760
W/dalvikvm( 1350): threadid=1: thread exiting with uncaught exception (group=0x41ce6e30)
E/AndroidRuntime( 1350): FATAL EXCEPTION: main
E/AndroidRuntime( 1350): Process: com.google.process.gapps, PID: 1350
E/AndroidRuntime( 1350): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1350): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1350): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1350): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1350): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1350): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1350): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1350): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1350): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1350): 	... 10 more
E/ActivityManager(  912): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
D/Process ( 1350): killProcess, pid=1350
I/DeviceManagement( 3742): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
D/Process ( 1350): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 3742): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 3742): WorkflowService: Starting workflow service
I/ActivityManager(  912): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 3742): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@422eecf0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 3742): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3742): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 3742): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 3742): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 3742): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 3742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3742): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca37c00
W/DeviceManagement( 3742): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@422eecf0]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 3742): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 3742): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 3742): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 3742): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 3742): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 3742): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 3742): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 3742): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 3742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 3742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 3742): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 3742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 3742): WorkflowService: Stopping workflow service
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4129 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  912): Recipient 1350
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.process.gapps (pid 1350) has died.
D/WifiService(  912): Client connection lost with reason: 4
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30861ms
D/Documents( 4129): Loading roots for com.android.providers.downloads.documents
D/Documents( 4129): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4129): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4129): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4129): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4129): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4129): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4129): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4129): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4129): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4129): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4129): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4129): threadid=1: thread exiting with uncaught exception (group=0x41ce6e30)
E/AndroidRuntime( 4129): FATAL EXCEPTION: main
E/AndroidRuntime( 4129): Process: com.android.documentsui, PID: 4129
E/AndroidRuntime( 4129): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4129): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4129): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4129): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4129): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4129): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4129): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4129): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4129): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4129): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4129): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4129): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4129): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4129): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4129): 	... 10 more
I/ActivityManager(  912): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4142 uid=10023 gids={50023, 1028, 1015, 1023}
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@421a8eb0 +
I/Prism.WidgetManager( 1250): onLoadItems() +
I/ActivityManager(  912): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4154 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  912): Killing 3780:com.htc.backup/1000 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=3780
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ActivityManager(  912): App crashed! Process: com.android.documentsui
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453986772273.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
D/Process ( 4129): killProcess, pid=4129
D/Process ( 4129): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ExternalStorage( 4142): After updating volumes, found 1 active roots
E/JavaBinder(  912): !!! FAILED BINDER TRANSACTION !!!
W/ContentService(  912): Found dead observer, removing
W/dalvikvm( 4154): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4154): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4154): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4154): install
I/MultiDex( 4154): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 4154): loading existing secondary dex files
I/MultiDex( 4154): load found 3 secondary dex files
I/MultiDex( 4154): install done
I/ActivityManager(  912): Recipient 4129
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Recipient 3780
I/ActivityManager(  912): Process com.android.documentsui (pid 4129) has died.
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
