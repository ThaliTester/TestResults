#### Test 502422852e23b2c_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/SensorService( 1018): [SO] activate (ident=0xb7ea4a78, enabled=0)
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/SurfaceFlinger(  258): id=11 createSurf (540x960),-1 flag=20004, DolorFade
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
D/SensorManager( 1018): unregisterListener ::   
D/KeyguardViewMediator( 1174): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1174): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1174): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1174): notifyScreenOffLocked
D/PowerManagerService( 1018): Excessive delay in ColorFade : createSurface: 17ms
D/KeyguardViewMediator( 1174): timeout : 5000
D/Launcher.HomeView( 1476): onPause
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 31ms
D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
V/TaskCloserActivity( 4921): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/KeyguardViewMediator( 1174): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1174): handleNotifyScreenOff
D/VolumePanel( 1174): onScreenTurnedOff()
D/VolumePanel( 1174): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1174): mCoverBroadcastReceiver: Screen OFF end
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
D/SecKeyguardClockSingleView( 1174): onScreenTurnedOff
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
V/ActivityThread( 1476): updateVisibility : ActivityRecord{3007c184 token=android.os.BinderProxy@10cc3ec9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1476): onStop
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/SamsungIME( 1748): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d6147fc
D/NotificationService( 1018): ACTION_SCREEN_OFF
I/WifiNative-HAL( 1018): Could not start hal
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1018): Bridge Server is not available
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1413): [EmergencyStateReceiver] binteractive [false] why[3]
D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1439): call the applyRouting
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
D/accuweather( 1577): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1577): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1577): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
D/accuweather( 1577): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1577): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1577): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1577): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
E/LibSecureUISvc( 1839): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/DisplayPowerState( 1018): !@ ColorFade entry
D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/lights  ( 1018): lcd : 0 +
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
D/SSRM:n  ( 1018): SIOP:: AP = 300
D/accuweather( 1577): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1577): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/lights  ( 1018): lcd : 0 -
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/accuweather( 1577): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1577): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1577): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/accuweather( 1577): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
D/accuweather( 1577): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(false) while turning screen off: 56ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(false): 59ms
D/DisplayManagerService( 1018): !@display_state: ON -> OFF
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb73ff690
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager( 1018): Display changed displayId=0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/StatusBar.NetworkController( 1174): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 243ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 244ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1932, ws=null) (elapsedTime=52010)
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 306ms
,D/AndroidRuntime( 5360): 
D/AndroidRuntime( 5360): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5360): CheckJNI is OFF
D/AndroidRuntime( 5360): readGMSProperty: start
D/AndroidRuntime( 5360): readGMSProperty: already setted!!
D/AndroidRuntime( 5360): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5360): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5360): readGMSProperty: end
D/AndroidRuntime( 5360): addProductProperty: start
E/AffinityControl( 5360): AffinityControl: registerfunction enter
D/AndroidRuntime( 5360): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5372): MountEmulatedStorage()
E/Zygote  ( 5372): v2
I/libpersona( 5372): KNOX_SDCARD checking this for 10345
I/libpersona( 5372): KNOX_SDCARD not a persona
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, iello
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5372 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/SELinux ( 5372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5372): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1476
D/AndroidRuntime( 5360): Shutting down VM
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5372): TimaSignature is unavailable
D/ActivityThread( 5372): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1476): updateVisibility : ActivityRecord{3007c184 token=android.os.BinderProxy@10cc3ec9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1476): onTrimMemory. Level: 20
I/WebViewFactory( 5372): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5372): Time to load native libraries: 2 ms (timestamps 7269-7271)
I/LibraryLoader( 5372): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5372): Binding Chromium to main looper Looper (main, tid 1) {31cb08d5}
I/LibraryLoader( 5372): Expected native library version number "",actual native library version number ""
I/chromium( 5372): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5372): Initializing chromium process, singleProcess=true
W/art     ( 5372): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5372): ApplicationContext is null in ApplicationStatus
W/chromium( 5372): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5372): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5372): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5372): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5372): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5372): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5372): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5372): Local Branch: 
I/Adreno-EGL( 5372): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5372): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5372):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 5360): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/BluetoothAdapter( 5372): 380049079: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5372): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5372): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5372): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5372): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5372): CordovaWebView is running on device made by: samsung
W/art     ( 5372): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5372): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{1079df39 u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5372): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 5372): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5372): updateVisibility : ActivityRecord{32f51ba7 token=android.os.BinderProxy@15823cc1 {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5372): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5372): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 5372
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5372): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5372): Initialized EGL, version 1.4
D/OpenGLRenderer( 5372): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5372): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5372): showStatusIcon on inactive InputConnection
I/Timeline( 5372): Timeline: Activity_idle id: android.os.BinderProxy@15823cc1 time:87839
I/ActivityManager( 1018): Displayed Component not be shown by security: +663ms (total +724ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1079df39 u0 com.example.hello/.MainActivity t19} time:87845
I/SurfaceFlinger(  258): id=12 Removed iello (7/9)
I/SurfaceFlinger(  258): id=12 Removed iello (-2/9)
I/SamsungIME( 1748): getCurrentCandidateView
W/BindingManager( 5372): Cannot call determinedVisibility() - never saw a connection for the pid: 5372
D/SamsungIME( 1748): Dismiss ExpandCandiate
I/SamsungIME( 1748): getDebugLevel  : 0x4f4c
I/SamsungIME( 1748): getDebugLevel  : 0x4f4c
I/chromium( 5372): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/SamsungIME( 1748): KeybaordView init() : load resources
I/SamsungIME( 1748): getCurrentKeyboard
I/SamsungIME( 1748): getTextKeyboard
D/SamsungIME( 1748): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5372): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5372): Unable to open asset URL: file:///android_asset/www/jxcore.js
E/SMD     (  289): DCD OFF
D/jxcore_app_log( 5372): JniHelper::setJavaVM(0xb75d1448), pthread_self() = -1213034608
D/JX-Cordova( 5372): jxcore cordova android initializing
W/jxcore-log( 5372): Initializing JXcore engine
W/jxcore-log( 5372): JXcore engine is ready
W/jxcore-log( 5372): Starting JXcore engine
,E/audit   ( 1798): type=1400 msg=audit(1449497294.817:203): avc:  denied  { ioctl } for  pid=5372 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1798):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1798): type=1300 msg=audit(1449497294.817:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beba0d58 items=0 ppid=308 ppcomm=main pid=5372 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1798): type=1320 msg=audit(1449497294.817:203): 
,W/jxcore-log( 5372): Platform android
W/jxcore-log( 5372): 
W/jxcore-log( 5372): Process ARCH arm
W/jxcore-log( 5372): 
,I/jxcore-log( 5372): JXcore Cordova bridge is ready!
I/jxcore-log( 5372): 
,W/jxcore-log( 5372): JXcore engine is started
,E/jxcore-log( 5372): >> samsung-SM-A300FU
E/jxcore-log( 5372): 
,I/jxcore-log( 5372): Total memory 1451114496
I/jxcore-log( 5372): 
,I/jxcore-log( 5372): Free memory 27160576
I/jxcore-log( 5372): 
I/jxcore-log( 5372): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5372): 
I/jxcore-log( 5372): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5372): 
,I/jxcore-log( 5372): userPath [ 'www' ]
I/jxcore-log( 5372): 
,I/jxcore-log( 5372): Size 540 960
I/jxcore-log( 5372): 
,I/jxcore-log( 5372): Screen Brightness 160
I/jxcore-log( 5372): 
,E/jxcore-log( 5372): Dummy Error Log.
E/jxcore-log( 5372): 
,I/jxcore-log( 5372): getBuffer is called!!!!
I/jxcore-log( 5372): 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardViewMediator( 1174): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1174): doKeyguard: not showing because lockscreen is off,
V/KeyguardEffectViewController( 1174): *** Keyguard wallpaper service already unbounded
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1932, ws=null) (elapsedTime=57011)
,D/BluetoothAdapter( 5372): disable()
,E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: false pid=5372, uid=10345
,D/SettingsProvider( 1018): name = wifi_on
,I/jxcore-log( 5372): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 5372): 
,I/jxcore-log( 5372): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5372): 
,D/AndroidRuntime( 5422): ,
D/AndroidRuntime( 5422): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5422): CheckJNI is OFF,
D/AndroidRuntime( 5422): readGMSProperty: start
D/AndroidRuntime( 5422): readGMSProperty: already setted!!,
D/AndroidRuntime( 5422): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5422): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5422): readGMSProperty: end
D/AndroidRuntime( 5422): addProductProperty: start
,E/AffinityControl( 5422): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5422): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1018): START PACKAGE DELETE: observer{685614200}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER,
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1,
,D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5372:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{258aa431 com.test.thalitest/10338} due to missing metadata
,I/WindowState( 1018): WIN DEATH: Window{8fa7963 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 5372,
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{1079df39 u0 com.example.hello/.MainActivity t19},
,W/ActivityManager( 1018): Spurious death for ProcessRecord{1b4bc751 5372:com.example.hello/u0a345}, curProc for 5372: null,
I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{1079df39 u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{1079df39 u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,E/SMD     (  289): DCD OFF
,I/art     ( 3732): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 692us total 23.203ms
,D/InputDispatcher( 1018): Focused application released
,I/art     ( 4145): Explicit concurrent mark sweep GC freed 22585(1675KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.076ms total 47.798ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1748): mOCRHelper is null
,W/GeofencerStateMachine( 1671): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3414): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:08:20 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3414): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5434): MountEmulatedStorage(),
E/Zygote  ( 5434): v2
I/libpersona( 5434): KNOX_SDCARD checking this for 10090
I/libpersona( 5434): KNOX_SDCARD not a persona
I/SELinux ( 5434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5434 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3414): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3414): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/TimaKeyStoreProvider( 5434): TimaSignature is unavailable
,D/ActivityThread( 5434): Added TimaKeyStore provider
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 24139(1797KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 2.513ms total 186.651ms
,I/art     ( 1018): WaitForGcToComplete blocked for 154.564ms for cause Explicit
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5434): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5434): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5434): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 5434): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5434): ElmAgentService : onCreate()
,D/elm:15121( 5434): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/KLMS-2.5.123: ( 3414): KLMSIntentService(): onDestroy()
,D/elm:15121( 5434): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5434): MDMBridge.getInstance()
D/elm:15121( 5434): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5434): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5434): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 4899:com.wssyncmldm/1000 (adj 15): empty #31
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10345
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1018): removeObsoleteFile: deleting file=19_task.xml
,V/EnterpriseBillingPolicy( 1018): uID is 10345
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 8120(409KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.218ms total 172.448ms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_PushUtil( 5095): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5095): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5095): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5095): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10345 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{685614200}
,I/SA      ( 5199): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5199): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/AndroidRuntime( 5422): Shutting down VM
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4365): PackagesMonitor onReceive :com.example.hello
,D/Mms/FreeMessageStatusReceiver( 4229): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4229): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4229): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1018): List of disabled apps :
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5149): onReceive() it will make start service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5149): onHandleIntent()
,D/Compatibility( 5149): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5149): found: 2
D/Compatibility( 5149): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5149): skipping ResolveInfo{19405d51 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5149): considering ResolveInfo{1a7c99b6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5149): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5149): enabling receiver ResolveInfo{16a716b7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 5455): MountEmulatedStorage()
E/Zygote  ( 5455): v2
I/libpersona( 5455): KNOX_SDCARD checking this for 10055
I/libpersona( 5455): KNOX_SDCARD not a persona
,I/SELinux ( 5455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5455 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 5455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5149): enabling receiver ResolveInfo{169a9e24 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5149): enabling receiver ResolveInfo{2fdc7d8d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5149): enabling receiver ResolveInfo{37309b42 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5149): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5455): TimaSignature is unavailable
,D/ActivityThread( 5455): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 5455): PlaceProvider onCreate()
,W/art     ( 5422): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UserAnalysis.SecureDbManager( 5455): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5455): SecurePlaceDbHelper() 
D/UserAnalysis( 5455): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5455): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5455): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 4460): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/IntelligenceServiceApplication( 5455): no applications having user consent for prediction
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,E/Zygote  ( 5472): MountEmulatedStorage()
,E/Zygote  ( 5472): v2
I/libpersona( 5472): KNOX_SDCARD checking this for 1000
I/libpersona( 5472): KNOX_SDCARD not a persona
I/SELinux ( 5472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5472 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
I/ActivityManager( 1018): Killing 4960:com.sec.android.app.camera/u0a135 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.,
V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/BluetoothAdapter( 5455): 489761166: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 5455): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5455): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/SQLiteLog( 5455): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 5455): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5455): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5455): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5455): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5455): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5455): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5455): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5455): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5455): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5455): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5455): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5455): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5455): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5455): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5455): It failed to get the database for dump_log
E/SQLiteLog( 5455): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 5472): TimaSignature is unavailable
E/SQLiteDatabase( 5455): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
E/SQLiteDatabase( 5455): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQL,iteDatabase.java:699)
E/SQLiteDatabase( 5455): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5455): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5455): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5455): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
E/SQLiteDatabase( 5455): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5455): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5455): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5455): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5455): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5455): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5455): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5455): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5455): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5455): It failed to get the database for dump_log
D/ActivityThread( 5472): Added TimaKeyStore provider
W/ResourcesManager( 5472): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/RCPManager( 5472):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5188): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5188): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FilterInstaller( 5188): FilterPackageService : ACTION_PACKAGE_REMOVED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,I/FilterInstaller( 5188): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5188): before removeFromFS
,E/Zygote  ( 5489): MountEmulatedStorage(),
E/Zygote  ( 5489): v2
I/libpersona( 5489): KNOX_SDCARD checking this for 1000
,I/libpersona( 5489): KNOX_SDCARD not a persona
,I/SELinux ( 5489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5489 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}

```
