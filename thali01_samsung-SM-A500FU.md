#### Test 5065027873d6a28_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
--------- beginning of system
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/PeopleContactsSync( 1990): CP2 sync disabled
V/WindowOrientationListener( 1019): WindowOrientationListener disabled
D/PowerManagerService( 1019): [s] UserActivityState : 2 -> 4
D/SensorService( 1019): [SO] activate (ident=0xb87463b0, enabled=0)
I/PowerManagerService( 1019): Nap time (uid 1000)...
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1019): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1019): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/SurfaceFlinger(  257): id=9 createSurf (720x1280),-1 flag=20004, DolorFade
I/PowerManagerService( 1019): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1019): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1019): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1019): handleSandman : startDream(true)
E/PowerManagerService( 1019): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1019): Sleeping (uid 1000)...
D/PowerManagerService( 1019): [s] UserActivityState : 4 -> 0
D/SensorManager( 1019): unregisterListener ::   
D/KeyguardViewMediator( 1183): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1183): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1183): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1183): notifyScreenOffLocked
D/Launcher.HomeView( 1472): onPause
D/Launcher( 1472): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PowerManagerService( 1019): Excessive delay in ColorFade : createSurface: 16ms
D/KeyguardViewMediator( 1183): timeout : 5000
D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1019): turn on LED for fully charged
E/lights  ( 1019): write_int failed to open -1
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardViewMediator( 1183): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1183): handleNotifyScreenOff
D/VolumePanel( 1183): onScreenTurnedOff()
D/VolumePanel( 1183): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1183): mCoverBroadcastReceiver: Screen OFF end
D/SecKeyguardClockSingleView( 1183): onScreenTurnedOff
E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/SmartFaceService( 1019): fail to set sysfs 0
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
D/PowerManagerService( 1019): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 39ms
D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService( 1019):  handler : SCREEN_OFF end 
V/ActivityThread( 1472): updateVisibility : ActivityRecord{1e5347b0 token=android.os.BinderProxy@2247a5b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1472): onStop
D/DisplayPowerController( 1019): ColorFade: onAnimationStart
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
I/StatusBar( 1183): Icon Only
D/PanelView( 1183): There is/are notification(s) 
D/NotificationService( 1019): ACTION_SCREEN_OFF
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9e8297fc
I/WifiNative-HAL( 1019): Could not start hal
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SamsungIME( 1802): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1990): Submit a task: h
I/BackgroundCompactionService( 1019): Schedule Type1 BGCompaction
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/PanelView( 1183): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/BackgroundCompactionService( 1019): onIdleStop
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1990): Processing package: com.test.thalitest
D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1019): Bridge Server is not available
D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PersonaManagerService( 1019): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_OFF called
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1409): [EmergencyStateReceiver] binteractive [false] why[3]
D/GassUtils( 1990): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/h       ( 1990): Found info for package com.test.thalitest in db.
D/NfcService( 1432): call the applyRouting
D/ActivityManager( 1019): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 4806): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5281): MountEmulatedStorage()
I/ActivityManager( 1019): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5281 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5281): v2
I/libpersona( 5281): KNOX_SDCARD checking this for 10010
I/libpersona( 5281): KNOX_SDCARD not a persona
I/SELinux ( 5281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/accuweather( 1713): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1713): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
I/SELinux ( 5281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5281): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1713): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/TimaKeyStoreProvider( 5281): TimaSignature is unavailable
D/ActivityThread( 5281): Added TimaKeyStore provider
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
D/DisplayPowerState( 1019): !@ ColorFade entry
D/DisplayPowerController( 1019): ColorFade: onAnimationEnd
D/lights  ( 1019): lcd : 0 +
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1019): stay LED for fully charged
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/lights  ( 1019): lcd : 0 -
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/QCOM PowerHAL( 1019): Got set_interactive hint
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayManagerService( 1019): !@display_state: ON -> OFF
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb8c6e690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1019): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1019): Display changed displayId=0
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/StatusBar.NetworkController( 1183): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/LibSecureUISvc( 1946): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:n  ( 1019): SIOP:: AP = 330
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
I/SL_DEBUG( 5250): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5250): isLoggable:: SL_DEBUG_EXIST = false
W/BaseAppContext( 1990): Using Auth Proxy for data requests.
I/BatteryStatsDumper( 1019): In refreshStats isReason Screen ON/OFF: true
I/ActivityManager( 1019): Killing 4323:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/BatteryStatsDumper( 1019): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1019): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1019): Previous Battery Level: 100 Current Level: 100 Delta: 0
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1019): Excessive delay in setPowerMode(): 264ms
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
D/PowerManagerService( 1019): Excessive delay in !@display_state: OFF: 264ms
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
I/libsuspend( 1019): !@autosuspend_wakeup_count_enable
I/libsuspend( 1019): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1019): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 286ms
I/PowerManagerService( 1019): [PWL] Off : 0s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1019, ws=null) (elapsedTime=131)
W/libprocessgroup( 1019): failed to open /acct/uid_10040/pid_4323/cgroup.procs: No such file or directory
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5250): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
I/art     ( 1607): Explicit concurrent mark sweep GC freed 11422(700KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 10MB/18MB, paused 1.120ms total 41.886ms
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5250): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/BatteryStatsDumper( 1019): Writing to database completed
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5311 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5311): MountEmulatedStorage()
I/libpersona( 5311): KNOX_SDCARD checking this for 10041
E/Zygote  ( 5311): v2
I/libpersona( 5311): KNOX_SDCARD not a persona
I/SELinux ( 5311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5311): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5311): TimaSignature is unavailable
D/ActivityThread( 5311): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 3822:com.google.android.talk/u0a104 (adj 15): empty #31
W/GAV2    ( 5146): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 5311): [SSP] onCreated
I/SA      ( 5311): [TPM] There is no property file
I/SA      ( 5311): [SCU] isHaveSA() - false
I/SA      ( 5311): [TPM] getModelProperty : null
I/SA      ( 5311): [TPM] getCSCProperty : null
I/SA      ( 5311): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5311): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5311): [DM] TFT FEATURE: false
I/SA      ( 5311): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5311): [DM] init START
W/libprocessgroup( 1019): failed to open /acct/uid_10104/pid_3822/cgroup.procs: No such file or directory
I/SA      ( 5311): [DM] This device is not a Vodafone
W/ResourceType( 5311): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5311): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5311): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5311): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5311): [SCU] isHaveSA() - false
I/SA      ( 5311): support phone number id : false
I/SA      ( 5311): [DM] Supports Ref Jpn : true
I/SA      ( 5311): [DM] init END
I/SA      ( 5311): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5311): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1019): Killing 4736:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5341): MountEmulatedStorage()
E/Zygote  ( 5341): v2
I/libpersona( 5341): KNOX_SDCARD checking this for 10100
I/libpersona( 5341): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5341 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5341): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Killing 4767:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SELinux ( 5341): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5341): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5146): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1019): failed to open /acct/uid_10069/pid_4736/cgroup.procs: No such file or directory
V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 5341): TimaSignature is unavailable
D/ActivityThread( 5341): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1990): Module APK com.google.android.play.games already loaded
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4767/cgroup.procs: No such file or directory
W/AccountFeatureHelper( 5146): Write apps_features disabled false
D/PackageIntentReceiver( 5341): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5341): Not GearManger package! 
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5364): MountEmulatedStorage()
I/libpersona( 5364): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5364): v2
I/libpersona( 5364): KNOX_SDCARD not a persona
I/SELinux ( 5364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5364 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5364): TimaSignature is unavailable
D/ActivityThread( 5364): Added TimaKeyStore provider
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4223:com.google.android.music:main/u0a111 (adj 15): empty #31
E/Zygote  ( 5379): MountEmulatedStorage()
I/libpersona( 5379): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5379): v2
I/libpersona( 5379): KNOX_SDCARD not a persona
I/SELinux ( 5379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5379): TimaSignature is unavailable
D/ActivityThread( 5379): Added TimaKeyStore provider
I/splitIntent( 1019): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1019): Killing 4864:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/AcmsPackageEventListener( 5379): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 5379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 5379): Enter Oncreate
D/AcmsServiceMonitor( 5379): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 5379): creating AcmsCore
D/AcmsCore( 5379): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5379): AcmsCore
D/AcmsCore( 5379): init
D/AcmsCore( 5379): Looper handler is not null
D/AcmsCore( 5379): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5379): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5379): Incrementing - Counter value: 1
D/AcmsCore( 5379): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5379): onStartCommand
D/AcmsService( 5379): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5379): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5379): Incrementing - Counter value: 2
D/AcmsService( 5379): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 5379): AcmsCertificateMngr
D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 5379): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr( 5379): AcmsRevocationMngr
W/libprocessgroup( 1019): failed to open /acct/uid_10111/pid_4223/cgroup.procs: No such file or directory
D/AcmsService( 5379): Inside handle Intent
D/AcmsService( 5379): App added - package name: com.test.thalitest
D/AcmsCore( 5379): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5379): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5379): Incrementing - Counter value: 3
D/AcmsCore( 5379): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5379): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5379): Decrementing - Counter value: 2
W/GAV2    ( 5146): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/libprocessgroup( 1019): failed to open /acct/uid_10142/pid_4864/cgroup.procs: No such file or directory
D/accuweather( 1713): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
D/accuweather( 1713): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1713): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1713): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1713): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 1713): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1713): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1713): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1713): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1713): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
D/accuweather( 1713): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/AndroidRuntime( 5397): 
D/AndroidRuntime( 5397): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5397): CheckJNI is OFF
D/AndroidRuntime( 5397): readGMSProperty: start
D/AndroidRuntime( 5397): readGMSProperty: already setted!!
D/AndroidRuntime( 5397): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5397): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5397): readGMSProperty: end
D/AndroidRuntime( 5397): addProductProperty: start
E/AffinityControl( 5397): AffinityControl: registerfunction enter
D/AndroidRuntime( 5397): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
E/Zygote  ( 5409): MountEmulatedStorage()
E/Zygote  ( 5409): v2
I/libpersona( 5409): KNOX_SDCARD checking this for 10175
I/libpersona( 5409): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5409 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=404, uhalitest
I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1472
D/AndroidRuntime( 5397): Shutting down VM
D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
D/ActivityThread( 5409): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ActivityManager( 1019): Killing 4909:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/9)
V/ActivityThread( 1472): updateVisibility : ActivityRecord{1e5347b0 token=android.os.BinderProxy@2247a5b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1472): onTrimMemory. Level: 20
I/WebViewFactory( 5409): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 5409): Time to load native libraries: 1 ms (timestamps 7889-7890)
I/LibraryLoader( 5409): Expected native library version number "",actual native library version number ""
W/art     ( 5397): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 5409): Binding Chromium to main looper Looper (main, tid 1) {30354aab}
I/LibraryLoader( 5409): Expected native library version number "",actual native library version number ""
I/chromium( 5409): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5409): Initializing chromium process, singleProcess=true,
,W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5409): ApplicationContext is null in ApplicationStatus,
,W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_4909/cgroup.procs: No such file or directory
,W/chromium( 5409): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 5409): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5409): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 5409): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 5409): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5409): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5409): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5409): Local Branch: 
I/Adreno-EGL( 5409): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5409): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5409):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5409): 904427956: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 5409): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5409): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5409): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5409): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5409): CordovaWebView is running on device made by: samsung
,W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5409): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 5409): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5409): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5409
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5409): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5409): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5409): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5409): Enabling debug mode 0
,V/ActivityThread( 5409): updateVisibility : ActivityRecord{1477b7e4 token=android.os.BinderProxy@17e42d76 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1183): Icon Only
,D/PanelView( 1183): There is/are notification(s) 
I/Timeline( 5409): Timeline: Activity_idle id: android.os.BinderProxy@17e42d76 time:88333
,W/IInputConnectionWrapper( 5409): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +590ms (total +680ms)
,I/SamsungIME( 1802): getCurrentCandidateView
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{33ea6802 u0 com.test.thalitest/.MainActivity t2} time:88350
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,D/SamsungIME( 1802): Dismiss ExpandCandiate
,W/BindingManager( 5409): Cannot call determinedVisibility() - never saw a connection for the pid: 5409
,D/AcmsKeyStoreHelper( 5379):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5379): Key Store exist
I/AcmsKeyStoreHelper( 5379): Hence loading the keystore file
,D/JsMessageQueue( 5409): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1802): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1802): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1802): KeybaordView init() : load resources
,D/AcmsKeyStoreHelper( 5379):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5379): getKeyStoreForApplication success 
D/AcmsCore( 5379): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5379): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5379): Decrementing - Counter value: 1
D/AcmsCore( 5379): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5379): This is NOT a valid MirrorLink app
D/AcmsCore( 5379): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5379): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5379): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5379): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5379): getSvcCounter - Counter value: 0
D/AcmsService( 5379): Enter onDestroy
I/AcmsService( 5379): cleanUp(): inside service clean up
D/AcmsCore( 5379): AcmsCore: inside DeInit
D/AcmsCore( 5379): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5379): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5379): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 5379): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 5379): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5379): getSvcCounter - Counter value: 0
,D/AcmsService( 5379): killing acms process
I/Process ( 5379): Sending signal. PID: 5379 SIG: 9
,I/SamsungIME( 1802): getCurrentKeyboard
,I/SamsungIME( 1802): getTextKeyboard
,E/SMD     (  288): DCD OFF
,D/SamsungIME( 1802): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 5409): JniHelper::setJavaVM(0xb7f49450), pthread_self() = -1203096296
,D/JX-Cordova( 5409): jxcore cordova android initializing
,I/ActivityManager( 1019): Process ACMS.Process (pid 5379)(adj 0) has died(51,1192)
,D/SamsungIME( 1802): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 5409): Initializing JXcore engine
W/jxcore-log( 5409): JXcore engine is ready
,W/jxcore-log( 5409): Starting JXcore engine,
,E/audit   ( 1933): type=1400 msg=audit(1449626603.671:203): avc:  denied  { ioctl } for  pid=5409 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1933):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1933): type=1300 msg=audit(1449626603.671:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=becdfd58 items=0 ppid=305 ppcomm=main pid=5409 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1933): type=1320 msg=audit(1449626603.671:203): 
,W/jxcore-log( 5409): Platform android
W/jxcore-log( 5409): 
W/jxcore-log( 5409): Process ARCH arm
W/jxcore-log( 5409): 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardViewMediator( 1183): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1183): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1183): *** Keyguard wallpaper service already unbounded
,I/jxcore-log( 5409): JXcore Cordova bridge is ready!
I/jxcore-log( 5409): 
,W/jxcore-log( 5409): JXcore engine is started
,I/Choreographer( 5409): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5409): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,E/jxcore  ( 5409): Error!: missing ) after argument list
E/jxcore  ( 5409): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5409): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 5409
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Killing 4928:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,W/PluginManager( 5409): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1019): mDVFSHelper.acquire(),
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1472): onRestart, Launcher: 894716242
,D/Launcher( 1472): onStart, Launcher: 894716242
,D/Launcher.HomeView( 1472): onStart
,D/Launcher( 1472): onResume, Launcher: 894716242
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10007
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1472): onResume
,D/Launcher( 1472): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1472): onResume
,D/ActivityManager( 1019): handle home activity for 0
,I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1019): post home show event for user 0
,D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/Launcher.HomeView( 1472): onPause
,I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/Launcher( 1472): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4338): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5463): MountEmulatedStorage()
,I/libpersona( 5463): KNOX_SDCARD checking this for 10088
E/Zygote  ( 5463): v2
I/libpersona( 5463): KNOX_SDCARD not a persona
,I/SELinux ( 5463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5463): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5463 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5463): TimaSignature is unavailable
,D/ActivityThread( 5463): Added TimaKeyStore provider
,E/Zygote  ( 5477): MountEmulatedStorage()
E/Zygote  ( 5477): v2
I/libpersona( 5477): KNOX_SDCARD checking this for 10142
I/libpersona( 5477): KNOX_SDCARD not a persona
,I/SELinux ( 5477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5477 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 4897): ui event
,I/SurfaceFlinger(  257): id=14 createSurf (720x1280),1 flag=4, Mauncher
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1472, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
W/ResourcesManager( 5463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/Recents_RecreateReceiver( 2415): onReceive by home
,D/InputDispatcher( 1019): Focus entered window: 1472,
D/TimaKeyStoreProvider( 5477): TimaSignature is unavailable
,D/ActivityThread( 5477): Added TimaKeyStore provider
,D/SRIB_DCS( 1472): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,V/ActivityThread( 1472): updateVisibility : ActivityRecord{1e5347b0 token=android.os.BinderProxy@2247a5b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1472): onStop
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_4928/cgroup.procs: No such file or directory
,W/IInputConnectionWrapper( 5409): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1802): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/StatusBar( 1183): Icon Only,
D/PanelView( 1183): There is/are notification(s) 
,V/TaskCloserActivity( 5477): TaskCloserActivity enter()
,E/Zygote  ( 5499): MountEmulatedStorage()
,E/Zygote  ( 5499): v2
I/libpersona( 5499): KNOX_SDCARD checking this for 10139
I/libpersona( 5499): KNOX_SDCARD not a persona
,I/SELinux ( 5499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/TaskCloserActivity( 5477): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/SELinux ( 5499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/Timeline( 1472): Timeline: Activity_idle id: android.os.BinderProxy@2247a5b6 time:91146
,E/SELinux ( 5499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5499 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4956:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/ActivityManager( 1019): Killing 4972:com.wsomacp/u0a25 (adj 15): empty #31
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3ce5ae06 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:91171
W/ActivityManager( 1019): mDVFSHelper.release()
,I/art     (  305): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 778us total 25.985ms
,D/TimaKeyStoreProvider( 5499): TimaSignature is unavailable
,D/ActivityThread( 5499): Added TimaKeyStore provider
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,W/ResourcesManager( 5499): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5499): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5499): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5499): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5499): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 596us total 22.156ms,
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 5028:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5477): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 18.515ms
,W/libprocessgroup( 1019): failed to open /acct/uid_10072/pid_4956/cgroup.procs: No such file or directory
,I/PowerManagerService( 1019): [PWL] Off : 5s ago
,W/libprocessgroup( 1019): failed to open /acct/uid_10025/pid_4972/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10012/pid_5028/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF,
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 254707(16MB) AllocSpace objects, 10(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.379ms total 207.527ms
D/ActivityManager( 1019): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 1019): [MSG] MCS_UNBIND
,I/ActivityManager( 1019): Killing 4657:com.samsung.aasaservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4657/cgroup.procs: No such file or directory
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 320,
,E/SMD     (  288): DCD OFF
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{1b47a8 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1019): onStart. jobID=801
,I/BackgroundCompactionService( 1019): onStart done. jobID=801
,I/BackgroundCompactionService( 1019): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1019): compact_memory command done
,D/Finsky  ( 4806): [826] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4806): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService( 1019): [PWL] Off : 15s ago
,E/SMD     (  288): DCD OFF
,D/FactoryTest( 4600): Not factory mode
,D/FactoryTest( 4600): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4600): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4600): still no open session command from host, so toast
,W/ContextImpl( 4600): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,I/Timeline( 4600): Timeline: Activity_launch_request id:com.android.settings time:105751
W/ContextImpl( 4600): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1019): Set to : 0
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 1472
,E/MTPRx   ( 4600): started activity for popup
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4600): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4600): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4600): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4600): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4600): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4600): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4600): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus entered window: 1472
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1019): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@342b705e attribute=null, token = android.os.BinderProxy@d506cc9
,D/SettingsReceiverActivity( 4600): dev.kiessupport is : TRUE
,D/PhoneWindow( 4600): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4600): *FMB* installDecor flags : 8388610
,D/SSRM:n  ( 1019): SIOP:: AP = 300,
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 3
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ActivityManager( 1019): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1019): [PWL] Off : 30s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :8,
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,I/PowerManagerService( 1019): [PWL] Off : 50s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 4
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 75s ago,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,V/AlarmManager( 1019): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1019): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1019): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss,
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/SecKeyguardClockView( 1183): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1183): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 5,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/ClearcutLoggerApiImpl( 1866): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate,
,D/SecKeyguardClockView( 1183): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/SecKeyguardClockView( 1183): HomeTimezone(): 1
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 11
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 12
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 13
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8,
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=426226 batch.start=797936
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
D/SecKeyguardClockView( 1183): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1183): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,W/ProcessCpuTracker( 1019): Skipping unknown process pid 5666
,W/ProcessCpuTracker( 1019): Skipping unknown process pid 5667
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 14
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 15
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,I/bootchecker(  312): bootchecker wake up!!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 16
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 18
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  315): Stop the daemon....
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 19
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 20
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 21,
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 22
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 23
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 24,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 680s ago,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 25,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4806): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1183): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1183): HomeTimezone(): 1
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1990): Aggregate from 1449625402489 (log), 1449625402489 (data)
,I/System.out( 4806): Thread-813(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4806): Thread-813(ApacheHTTPLog):isShipBuild true
I/System.out( 4806): Thread-813(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4806): Thread-813(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,I/System.out( 4806): Thread-813 calls detatch()
,W/Finsky  ( 4806): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Watchdog( 1019): !@Sync 26
,I/System.out( 4806): Thread-814(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4806): Thread-814(ApacheHTTPLog):isShipBuild true
I/System.out( 4806): Thread-814(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4806): Thread-814(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4806): Thread-814 calls detatch()
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): Thread-813(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4806): Thread-813(ApacheHTTPLog):isShipBuild true
I/System.out( 4806): Thread-813(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4806): Thread-813(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4806): Thread-813 calls detatch()
,W/Finsky  ( 4806): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): Thread-814(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4806): Thread-814(ApacheHTTPLog):isShipBuild true
I/System.out( 4806): Thread-814(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4806): Thread-814(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4806): Thread-814 calls detatch()
,W/Finsky  ( 4806): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4806): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4806): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1019): waitForAlarm result :4
,D/Finsky  ( 4806): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/ActivityManager( 1019): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
D/DeviceConnectionService( 1866): client connected with version: 8296000
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4806): [840] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4806): [826] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4806): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 27
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 765s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 28
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 29
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 30
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 31
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 32,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 33
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 950s ago,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 34
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 35,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
D/BatteryService( 1019): stay LED for fully charged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 36
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 37,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1050s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 38
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 39
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1449627729695
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1449627729698
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 40
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 41
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 42
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 43
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 44
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1265s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 45
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 46
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 47,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 48
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1380s ago,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 49
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 50,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 51
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 52
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1500s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 53
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1019): !@Sync 54
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1019): !@Sync 55
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1019): !@Sync 56
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1625s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 57
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 58
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 59
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 60
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1755s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 61
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1019): Killing 5089:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3583:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
,I/ActivityManager( 1019): Killing 4694:com.google.android.partnersetup/u0a15 (adj 15): empty #33
,I/ActivityManager( 1019): Killing 2999:com.wssyncmldm/1000 (adj 15): SPC_empty #34
,I/ActivityManager( 1019): Killing 4073:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #35
,I/ActivityManager( 1019): Killing 3496:com.samsung.hs20settings/1000 (adj 15): SPC_empty #36
,I/ActivityManager( 1019): Killing 2589:com.sec.phone/1001 (adj 15): SPC_empty #37
,I/ActivityManager( 1019): Killing 2872:com.sec.bcservice/1000 (adj 15): SPC_empty #38
,I/ActivityManager( 1019): Killing 2701:com.samsung.android.providers.context/u0a3 (adj 15): SPC_empty #39
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1019): Prepared write state in 20ms
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4806): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.phone/.SecPhoneService in 1000ms
,D/GpsStatusListenerHelper( 1019): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@9131bb7
,W/ActivityManager( 1019): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3636864ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10992ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 20989ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 30985ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.wssyncmldm/.XDMService in 40970ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-48-54.bin
,W/libprocessgroup( 1019): failed to open /acct/uid_10047/pid_5089/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1001/pid_2589/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10015/pid_4694/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_2701/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10116/pid_4073/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3496/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3583/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2872/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2999/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6263): MountEmulatedStorage()
,E/Zygote  ( 6263): v2
I/libpersona( 6263): KNOX_SDCARD checking this for 10116,
I/libpersona( 6263): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=6263 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/SELinux ( 6263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6263): TimaSignature is unavailable
,D/ActivityThread( 6263): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 6263): onCreate mCpBitFlag=0
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6283): MountEmulatedStorage()
,E/Zygote  ( 6283): v2
I/libpersona( 6283): KNOX_SDCARD checking this for 1000
I/libpersona( 6283): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=6283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6283): TimaSignature is unavailable
,D/ActivityThread( 6283): Added TimaKeyStore provider
,I/Hs20UtilService( 6283): onCreate
,I/Hs20UtilService( 6283): Starting #2
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 62
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6307): MountEmulatedStorage(),
E/Zygote  ( 6307): v2
I/libpersona( 6307): KNOX_SDCARD checking this for 1000
I/libpersona( 6307): KNOX_SDCARD not a persona
,I/SELinux ( 6307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=6307 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6307): TimaSignature is unavailable
D/ActivityThread( 6307): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4783:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,W/ResourcesManager( 6307): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 6307): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 6307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1019): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6322): MountEmulatedStorage(),
E/Zygote  ( 6322): v2
I/libpersona( 6322): KNOX_SDCARD checking this for 1001
I/libpersona( 6322): KNOX_SDCARD not a persona
,I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=6322 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a,
,I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable
,D/ActivityThread( 6322): Added TimaKeyStore provider
,W/ResourcesManager( 6322): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 6307): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 6307): default registerAction()
I/F_PHONE ( 6307): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  288): DCD OFF
,W/libprocessgroup( 1019): failed to open /acct/uid_10120/pid_4783/cgroup.procs: No such file or directory,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1019): Killing 5281:com.sec.android.app.samsungapps/u0a10 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5233:com.sec.spp.push/u0a35 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 4673:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5198:com.sec.android.app.soundalive/u0a53 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 5185:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty for 1800s
I/ActivityManager( 1019): Killing 5167:com.policydm/1000 (adj 15): empty for 1801s
,I/ActivityManager( 1019): Killing 5137:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty for 1801s
,I/ActivityManager( 1019): Killing 4718:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty for 1801s
I/ActivityManager( 1019): Killing 4751:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
I/ActivityManager( 1019): Killing 5120:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty for 1801s
,I/ActivityManager( 1019): Killing 5101:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,V/NetworkStats( 1019): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,V/NetworkStats( 1019): performPollLocked() took 5ms
,D/SecKeyguardClockView( 1183): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/SecKeyguardClockView( 1183): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
I/BatteryStatsDumper( 1019): In refreshStats isReason Screen ON/OFF: false
,I/Icing   ( 1990): Performing maintenance.
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
,W/Icing   ( 1990): Received bad json for section weights override -- ignoring.
,W/Icing   ( 1990): Received bad json for corpus context scoring override -- ignoring.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BatteryStatsDumper( 1019): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1019): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1019): Previous Battery Level: 100 Current Level: 100 Delta: 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1019): failed to open /acct/uid_10010/pid_5281/cgroup.procs: No such file or directory
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4718/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10035/pid_5233/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5167/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10057/pid_4673/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5120/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4751/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10156/pid_5185/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5101/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10053/pid_5198/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5137/cgroup.procs: No such file or directory
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 1607): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,I/System.out( 1607): (HTTPLog)-Static: isSBSettingEnabled false
,W/Icing   ( 1990): Failed to get auth token for account:<redacted>, error:NetworkError
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1607): (HTTPLog)-Static: isSBSettingEnabled false
,W/Icing   ( 1990): Failed to get auth token for account:<redacted>, error:NetworkError
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 5250:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty for 1800s
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6356): MountEmulatedStorage()
,E/Zygote  ( 6356): v2
I/libpersona( 6356): KNOX_SDCARD checking this for 10057
I/libpersona( 6356): KNOX_SDCARD not a persona
,I/SELinux ( 6356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.UdcSettingBroadcastReceiver: pid=6356 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
I/SELinux ( 6356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6356): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SMD     (  288): DCD OFF
,W/libprocessgroup( 1019): failed to open /acct/uid_10038/pid_5250/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6356): TimaSignature is unavailable
,D/ActivityThread( 6356): Added TimaKeyStore provider
,I/Icing   ( 1990): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 1990): Performing maintenance usage 1790177 budget 4905216112 free 99.964% index free 99.977% purge? false target 3433651278
,I/art     ( 1019): Background partial concurrent mark sweep GC freed 73047(8MB) AllocSpace objects, 336(5MB) LOS objects, 33% free, 27MB/41MB, paused 2.723ms total 181.561ms
,I/BatteryStatsDumper( 1019): Writing to database completed
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 5311:com.osp.app.signin/u0a41 (adj 15): empty for 1800s
,D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1019): getProviders()=[passive]
,E/Zygote  ( 6377): MountEmulatedStorage(),
I/libpersona( 6377): KNOX_SDCARD checking this for 10015
,E/Zygote  ( 6377): v2
,I/libpersona( 6377): KNOX_SDCARD not a persona
I/SELinux ( 6377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6377 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6377): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 5146:com.google.android.apps.docs/u0a91 (adj 15): empty for 1800s
,W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_5311/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6377): TimaSignature is unavailable
,D/ActivityThread( 6377): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 5341:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1800s,
,I/ActivityManager( 1019): Killing 5364:com.samsung.helphub/1000 (adj 15): empty for 1800s
,E/SQLiteLog( 1607): (10) POSIX Error : 11 SQLite Error : 3850
,W/libprocessgroup( 1019): failed to open /acct/uid_10091/pid_5146/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10100/pid_5341/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5364/cgroup.procs: No such file or directory
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ActivityManager( 1019): Killing 5409:com.test.thalitest/u0a175 (adj 15): empty for 1800s
,I/ActivityManager( 1019): Killing 4338:com.sec.android.gallery3d/u0a44 (adj 15): empty for 1800s
,W/libprocessgroup( 1019): failed to open /acct/uid_10044/pid_4338/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10175/pid_5409/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  288): DCD OFF
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
V/EmergencyMode( 1409): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1409): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  ( 1019): SIOP:: AP = 260
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 6400): 
D/AndroidRuntime( 6400): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6400): CheckJNI is OFF
D/AndroidRuntime( 6400): readGMSProperty: start
D/AndroidRuntime( 6400): readGMSProperty: already setted!!
D/AndroidRuntime( 6400): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6400): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6400): readGMSProperty: end
D/AndroidRuntime( 6400): addProductProperty: start
E/AffinityControl( 6400): AffinityControl: registerfunction enter
D/AndroidRuntime( 6400): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{426865952}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{13e807fb com.example.hello/10174} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3737): Explicit concurrent mark sweep GC freed 2583(158KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 821us total 46.297ms
I/art     ( 4581): Explicit concurrent mark sweep GC freed 15066(807KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 859us total 59.935ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1802): mOCRHelper is null
W/GeofencerStateMachine( 1866): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3518): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 03:33:38 GMT+01:00 2015
D/ActivityManager( 1019): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1432): Collect Tech packages for Knox
I/KLMS-2.5.183: ( 3518): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1019): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/PersonaManager( 1432): isKioskContainerExistOnDevice
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onCreate()
E/Zygote  ( 6413): MountEmulatedStorage()
E/Zygote  ( 6413): v2
I/libpersona( 6413): KNOX_SDCARD checking this for 10044
I/libpersona( 6413): KNOX_SDCARD not a persona
I/SELinux ( 6413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6413): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6413 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3518): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3518): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  ( 6425): MountEmulatedStorage()
E/Zygote  ( 6425): v2
I/libpersona( 6425): KNOX_SDCARD checking this for 10149
I/libpersona( 6425): KNOX_SDCARD not a persona
I/SELinux ( 6425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6425 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): PACKAGE_REMOVED
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
D/TimaKeyStoreProvider( 6413): TimaSignature is unavailable
D/ActivityThread( 6413): Added TimaKeyStore provider
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  ( 6438): MountEmulatedStorage()
E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 10094
I/SELinux ( 6438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6438): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6438 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/art     ( 1019): Explicit concurrent mark sweep GC freed 26115(1951KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 27MB/40MB, paused 3.644ms total 229.829ms
I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/art     ( 1019): WaitForGcToComplete blocked for 148.374ms for cause Explicit
E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6425): TimaSignature is unavailable
D/PersonaManager( 1432): isKioskContainerExistOnDevice
D/ActivityThread( 6425): Added TimaKeyStore provider
E/SMD     (  288): DCD OFF
I/art     ( 4581): Explicit concurrent mark sweep GC freed 890(40KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 724us total 26.398ms
D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
D/ActivityThread( 6438): Added TimaKeyStore provider
D/RegisteredServicesCache( 1432): empty dynamic service
E/SQLiteLog( 4581): (284) automatic index on crash_info_summary(package_name_touched)
W/ResourcesManager( 6413): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6459): MountEmulatedStorage()
I/libpersona( 6459): KNOX_SDCARD checking this for 10072
E/Zygote  ( 6459): v2
I/libpersona( 6459): KNOX_SDCARD not a persona
I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6459 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6438): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6438): ELMEngine.ELMEngine( context ).
D/elm:15183( 6438): MDMBridge.setEnterpriseBridge()
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): listeningToPackageRemoved().END
E/Zygote  ( 6469): MountEmulatedStorage()
I/libpersona( 6469): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6469): v2
I/libpersona( 6469): KNOX_SDCARD not a persona
I/SELinux ( 6469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6469 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/ActivityManager( 1019): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
E/SELinux ( 6469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ThemeInfoUtil( 6425): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6425): isCurrentFestival = false
D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
D/elm:15183( 6438): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityThread( 6459): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onDestroy()
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
I/art     (  305): Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.296ms total 27.071ms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6438): ElmAgentService : onCreate()
D/elm:15183( 6438): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6438): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6438): MDMBridge.getInstance()
D/elm:15183( 6438): MDMBridge.getAllLicenseInfoFromSDK()
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.959ms
D/TimaKeyStoreProvider( 6469): TimaSignature is unavailable
D/elm:15183( 6438): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityThread( 6469): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 17.307ms
E/Zygote  ( 6491): MountEmulatedStorage()
I/libpersona( 6491): KNOX_SDCARD checking this for 10152
E/Zygote  ( 6491): v2
I/libpersona( 6491): KNOX_SDCARD not a persona
I/SELinux ( 6491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6491 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Killing 4897:com.android.mms/u0a46 (adj 15): empty for 1813s
E/SELinux ( 6491): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/elm:15183( 6438): ElmAgentService : onDestroy().
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6491): TimaSignature is unavailable
D/ActivityThread( 6491): Added TimaKeyStore provider
W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
E/Zygote  ( 6503): MountEmulatedStorage()
I/libpersona( 6503): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6503): v2
I/libpersona( 6503): KNOX_SDCARD not a persona
I/SELinux ( 6503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 5463:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty for 1813s
I/ActivityManager( 1019): Killing 5499:com.sec.android.app.camera/u0a139 (adj 15): empty for 1813s
I/art     ( 1019): Explicit concurrent mark sweep GC freed 7269(339KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 4.738ms total 293.276ms
D/CountryDetector( 1019): No listener is left
D/TimaKeyStoreProvider( 6503): TimaSignature is unavailable
D/ActivityThread( 6503): Added TimaKeyStore provider
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BadgeProvider( 6459): onCreate
D/BadgeProvider( 6459): DatabaseHelper
W/ContextImpl( 6469): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
D/NearbySource( 6413): Nearby Source Create!
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/BadgeProvider( 6459): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6459): sendNotify, [notify] : null
D/BadgeProvider( 6459): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6459): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6459): update, [UpdateCount] : 1
D/NearbyContext( 6413): Nearby Context Create!
D/PackageManager( 1019): delete codoeFile: 
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10175 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{426865952}
D/AASAservice-UpdateReceiver( 6503): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6503): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/System.err( 6503): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6503): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6503): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6503): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6503): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6503): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6503): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6503): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6503): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6400): Shutting down VM
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 6524): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6524): MountEmulatedStorage()
I/libpersona( 6524): KNOX_SDCARD not a persona
E/Zygote  ( 6524): v2
I/SELinux ( 6524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SQLiteLog( 6491): (284) automatic index on shooting_modes(title_id)
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6413): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6413): Samsung link source created
I/ActivityManager( 1019): Killing 5477:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty for 1813s
D/TimaKeyStoreProvider( 6524): TimaSignature is unavailable
D/ActivityThread( 6524): Added TimaKeyStore provider
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/ActivityManager( 1019): Killing 5007:com.android.defcontainer/u0a4 (adj 15): empty for 1809s
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1019): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1019): OtpDbHelper::getInstance New instance created
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/OTPFW   ( 1019): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1019): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1019): ProvisionData::getAllEntries Enter
W/ResourcesManager( 6524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/OTPFW   ( 1019): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10175
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6540): MountEmulatedStorage()
I/libpersona( 6540): KNOX_SDCARD checking this for 10156
E/Zygote  ( 6540): v2
I/libpersona( 6540): KNOX_SDCARD not a persona
I/SELinux ( 6540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6540 uid=10156 gids={50156, 9997} abi=armeabi-v7a
E/SELinux ( 6540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1019): uID is 10175
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1019): removeObsoleteFile: deleting file=2_task.xml
D/TimaKeyStoreProvider( 6540): TimaSignature is unavailable
D/ActivityThread( 6540): Added TimaKeyStore provider
D/RCPManager( 6524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1019):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
V/AlarmManagerEXT( 1019): com.test.thalitest(10175) is removed.
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 6553): MountEmulatedStorage()
E/Zygote  ( 6553): v2
I/libpersona( 6553): KNOX_SDCARD checking this for 1000
I/libpersona( 6553): KNOX_SDCARD not a persona
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 6553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1019): onPackageRemoved : com.test.thalitest
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
W/libprocessgroup( 1019): failed to open /acct/uid_10046/pid_4897/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_5463/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_5499/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10142/pid_5477/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10004/pid_5007/cgroup.procs: No such file or directory
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6553): TimaSignature is unavailable
D/ActivityThread( 6553): Added TimaKeyStore provider
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/Launcher.Model( 1472): reloadBadges entered.
E/Zygote  ( 6571): MountEmulatedStorage()
I/libpersona( 6571): KNOX_SDCARD checking this for 10091
E/Zygote  ( 6571): v2
I/libpersona( 6571): KNOX_SDCARD not a persona
I/SELinux ( 6571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38

```
