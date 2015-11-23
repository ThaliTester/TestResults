#### Test 503880196b4ec73_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  296): DCD OFF
,D/AndroidRuntime( 5344): 
D/AndroidRuntime( 5344): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5344): CheckJNI is OFF
D/AndroidRuntime( 5344): readGMSProperty: start
D/AndroidRuntime( 5344): readGMSProperty: already setted!!
D/AndroidRuntime( 5344): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5344): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5344): readGMSProperty: end
D/AndroidRuntime( 5344): addProductProperty: start
E/AffinityControl( 5344): AffinityControl: registerfunction enter
D/AndroidRuntime( 5344): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
D/Launcher.HomeView( 1481): onPause
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1481
D/AndroidRuntime( 5344): Shutting down VM
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
V/TaskCloserActivity( 4920): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5357): MountEmulatedStorage()
E/Zygote  ( 5357): v2
I/libpersona( 5357): KNOX_SDCARD checking this for 10345
I/libpersona( 5357): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5357 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/ActivityThread( 1481): updateVisibility : ActivityRecord{8c28425 token=android.os.BinderProxy@bcc7ae8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/SELinux ( 5357): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5357): TimaSignature is unavailable
D/ActivityThread( 5357): Added TimaKeyStore provider
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/ActivityManager( 1021): Display changed displayId=0
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PowerManagerService( 1021): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1021): Nap time (uid 1000)...
D/PowerManagerService( 1021): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1021): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1021): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1021): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1021): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1021): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1021): handleSandman : startDream(true)
V/WindowOrientationListener( 1021): WindowOrientationListener disabled
D/Launcher.HomeView( 1481): onStop
D/SensorService( 1021): [SO] activate (ident=0xb8cac868, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
V/ActivityThread( 1481): updateVisibility : ActivityRecord{8c28425 token=android.os.BinderProxy@bcc7ae8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/SensorManager( 1021): unregisterListener ::   
D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1175): notifyScreenOffLocked
D/KeyguardViewMediator( 1175): timeout : 5000
E/PowerManagerService( 1021): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1021): Sleeping (uid 1000)...
D/PowerManagerService( 1021): [s] UserActivityState : 4 -> 0
I/SurfaceFlinger(  259): id=12 createSurf (540x960),-1 flag=20004, DolorFade
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1175): handleNotifyScreenOff
D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
D/PowerManagerService( 1021): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 26ms
D/DisplayPowerController( 1021): ColorFade: onAnimationStart
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/Launcher( 1481): onTrimMemory. Level: 20
D/LightsService( 1021): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1021) 
D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1021): turn on LED for fully charged
E/lights  ( 1021): write_int failed to open -1
D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/SmartFaceService( 1021): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1021): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1021): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1021): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1021): fail to set sysfs 0
W/System.err( 1021): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1021): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1021): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1021): 	... 10 more
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/MotionRecognitionService( 1021):   mReceiver.onReceive : ACTION_SCREEN_OFF
W/art     ( 5344): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/MotionRecognitionService( 1021):  handler : SCREEN_OFF end 
I/WifiNative-HAL( 1021): startHal
E/wifi    ( 1021): getStaticLongField sWifiHalHandle 0x9d4957fc
D/NotificationService( 1021): ACTION_SCREEN_OFF
I/WifiNative-HAL( 1021): Could not start hal
W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/LightsService( 1021): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 1021) 
D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1021): write_int failed to open -1
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
D/audio_hw_primary(  288): adev_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  288): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  288): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  288): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  288): adev_set_parameters: exit
I/WebViewFactory( 5357): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
D/IpRemoteDisplayController( 1021): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1021): Bridge Server is not available
D/GpsLocationProvider( 1021): receive broadcast intent, action: android.intent.action.SCREEN_OFF
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1401): [EmergencyStateReceiver] binteractive [false] why[3]
D/PersonaManagerService( 1021): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1021): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1440): call the applyRouting
D/accuweather( 1556): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1556): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/LibraryLoader( 5357): Time to load native libraries: 32 ms (timestamps 5999-6031)
I/LibraryLoader( 5357): Expected native library version number "",actual native library version number ""
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
D/accuweather( 1556): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/daemonapp( 1601): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
D/accuweather( 1556): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1556): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1556): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1556): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1021): stay LED for fully charged
D/daemonapp( 1601): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/WebViewChromiumFactoryProvider( 5357): Binding Chromium to main looper Looper (main, tid 1) {8f32653}
I/LibraryLoader( 5357): Expected native library version number "",actual native library version number ""
I/chromium( 5357): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/DisplayPowerState( 1021): !@ ColorFade entry
D/DisplayPowerController( 1021): ColorFade: onAnimationEnd
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/lights  ( 1021): lcd : 0 +
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
I/BrowserStartupController( 5357): Initializing chromium process, singleProcess=true
W/art     ( 5357): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5357): ApplicationContext is null in ApplicationStatus
D/lights  ( 1021): lcd : 0 -
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event1/device/enabled: 0
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event3/device/enabled: 0
E/LibSecureUISvc( 1803): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:n  ( 1021): SIOP:: AP = 310
D/daemonapp( 1601): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/chromium( 5357): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/accuweather( 1556): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1556): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1556): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1556): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/chromium( 5357): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/accuweather( 1556): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/accuweather( 1556): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
E/libEGL  ( 5357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5357): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5357): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5357): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5357): Local Branch: 
I/Adreno-EGL( 5357): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5357): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5357):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/accuweather( 1556): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 1021): Excessive delay in MISC setInteractive(false) while turning screen off: 60ms
I/QCOM PowerHAL( 1021): Got set_interactive hint
D/PowerManagerService( 1021): Excessive delay in nativeSetInteractive(false): 64ms
D/DisplayManagerService( 1021): !@display_state: ON -> OFF
I/DisplayManagerService( 1021): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1021): Display changed displayId=0
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb77a8690
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BluetoothAdapter( 5357): 496308412: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{89d7c83 u0 com.example.hello/.MainActivity t19}
W/art     ( 5357): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5357): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5357): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5357): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5357): CordovaWebView is running on device made by: samsung
W/art     ( 5357): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5357): Attempt to remove local handle scope entry from IRT, ignoring
I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1021): Excessive delay in setPowerMode(): 245ms
D/PowerManagerService( 1021): Excessive delay in !@display_state: OFF: 246ms
I/libsuspend( 1021): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1021): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 310ms
I/libsuspend( 1021): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1021): [PWL] Off : 0s ago
I/PowerManagerService( 1021): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1021): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1924, ws=null) (elapsedTime=53220)
I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=1021, ws=null) (elapsedTime=555)
E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
D/OpenGLRenderer( 5357): Render dirty regions requested: true
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
W/chromium( 5357): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5357): updateVisibility : ActivityRecord{2e0a1cb5 token=android.os.BinderProxy@1dd5479f {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5357): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5357): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1021): Focus entered window: 5357
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 5357): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5357): Initialized EGL, version 1.4
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 5357): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5357): Enabling debug mode 0
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5357): showStatusIcon on inactive InputConnection
I/Timeline( 5357): Timeline: Activity_idle id: android.os.BinderProxy@1dd5479f time:86658
D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{89d7c83 u0 com.example.hello/.MainActivity t19} time:86666
I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
W/BindingManager( 5357): Cannot call determinedVisibility() - never saw a connection for the pid: 5357
I/SamsungIME( 1841): getCurrentCandidateView
I/chromium( 5357): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1841): Dismiss ExpandCandiate
,I/SamsungIME( 1841): getDebugLevel  : 0x4f4c
I/SamsungIME( 1841): getDebugLevel  : 0x4f4c
I/SamsungIME( 1841): KeybaordView init() : load resources
D/JsMessageQueue( 5357): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1841): getCurrentKeyboard
I/SamsungIME( 1841): getTextKeyboard
E/AndroidProtocolHandler( 5357): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SamsungIME( 1841): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 5357): JniHelper::setJavaVM(0xb81cd448), pthread_self() = -1200463144
D/JX-Cordova( 5357): jxcore cordova android initializing
W/jxcore-log( 5357): Initializing JXcore engine
W/jxcore-log( 5357): JXcore engine is ready
W/jxcore-log( 5357): Starting JXcore engine
E/audit   ( 1793): type=1400 msg=audit(1448306476.613:203): avc:  denied  { ioctl } for  pid=5357 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1793):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1793): type=1300 msg=audit(1448306476.613:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bea20d58 items=0 ppid=315 ppcomm=main pid=5357 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1793): type=1320 msg=audit(1448306476.613:203): 
W/jxcore-log( 5357): Platform android
W/jxcore-log( 5357): 
W/jxcore-log( 5357): Process ARCH arm
W/jxcore-log( 5357): 
I/jxcore-log( 5357): JXcore Cordova bridge is ready!
I/jxcore-log( 5357): 
W/jxcore-log( 5357): JXcore engine is started
E/jxcore-log( 5357): >> samsung-SM-A300FU
E/jxcore-log( 5357): 
I/jxcore-log( 5357): Total memory 1451114496
I/jxcore-log( 5357): 
I/jxcore-log( 5357): Free memory 27213824
I/jxcore-log( 5357): 
I/jxcore-log( 5357): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5357): 
I/jxcore-log( 5357): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5357): 
I/jxcore-log( 5357): userPath [ 'www' ]
I/jxcore-log( 5357): 
I/jxcore-log( 5357): Size 540 960
I/jxcore-log( 5357): 
I/jxcore-log( 5357): Screen Brightness 160
I/jxcore-log( 5357): 
E/jxcore-log( 5357): Dummy Error Log.
E/jxcore-log( 5357): 
,I/jxcore-log( 5357): getBuffer is called!!!!
I/jxcore-log( 5357): 
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 5s ago
,I/PowerManagerService( 1021): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1021): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1924, ws=null) (elapsedTime=58222)
,D/BluetoothAdapter( 5357): disable()
,E/BluetoothManagerService( 1021): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1021): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1021): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1021): mCursor = null
,D/WifiService( 1021): setWifiEnabled: false pid=5357, uid=10345
,D/SettingsProvider( 1021): name = wifi_on
,I/jxcore-log( 5357): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 5357): 
,I/jxcore-log( 5357): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5357): 
,D/AndroidRuntime( 5412): 
D/AndroidRuntime( 5412): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5412): CheckJNI is OFF
,D/AndroidRuntime( 5412): readGMSProperty: start
D/AndroidRuntime( 5412): readGMSProperty: already setted!!
D/AndroidRuntime( 5412): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5412): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5412): readGMSProperty: end
D/AndroidRuntime( 5412): addProductProperty: start
,E/AffinityControl( 5412): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5412): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 1021): START PACKAGE DELETE: observer{106903618}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
D/PackageManagerService( 1021): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1021): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 5357:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1021): Skipping PackageSetting{2395b8ab com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{89d7c83 u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1021): Focus left window: 5357
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1021): Focused application released
,E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3662): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 684us total 32.861ms
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4140): Explicit concurrent mark sweep GC freed 19316(1233KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.343ms total 54.092ms
,E/SamsungIME( 1841): mOCRHelper is null
,W/GeofencerStateMachine( 1657): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3442): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 20:21:22 GMT+01:00 2015
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3442): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5425): MountEmulatedStorage(),
E/Zygote  ( 5425): v2
I/libpersona( 5425): KNOX_SDCARD checking this for 10090
I/libpersona( 5425): KNOX_SDCARD not a persona
,I/SELinux ( 5425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): onCreate()
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5425 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3442): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3442): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 5425): TimaSignature is unavailable
,D/ActivityThread( 5425): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 67972(4MB) AllocSpace objects, 21(450KB) LOS objects, 33% free, 23MB/35MB, paused 3.054ms total 175.059ms
,I/art     ( 1021): WaitForGcToComplete blocked for 116.711ms for cause Explicit
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/elm:15121( 5425): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5425): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5425): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5425): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5425): ElmAgentService : onCreate()
,D/RCPManagerService( 1021): PackageReceiver onReceive()
,I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5425): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5425): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 5425): MDMBridge.getInstance()
,D/elm:15121( 5425): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5425): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5425): ElmAgentService : onDestroy().
,I/ActivityManager( 1021): Killing 4883:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): listeningToPackageRemoved().END
D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
,I/KLMS-2.5.123: ( 3442): KLMSIntentService(): onDestroy()
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10345
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1021): uID is 10345
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
D/TaskPersister( 1021): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 5086): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5086): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5086): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5086): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5194): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5194): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 13578(763KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.735ms total 193.366ms
,I/art     ( 1021): WaitForGcToComplete blocked for 306.548ms for cause Explicit
,I/PackagesMonitor( 4364): PackagesMonitor onReceive :com.example.hello
,D/Mms/FreeMessageStatusReceiver( 4213): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1021): enable value -1
,I/TactileAssist( 1021): internal enable value -1
,I/TactileAssist( 1021): intensity value -1
I/TactileAssist( 1021): saveAppList value true
,I/TactileAssist( 1021): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4213): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4213): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/Compatibility( 5143): onReceive() it will make start service
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5143): onHandleIntent()
D/Compatibility( 5143): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5143): found: 2
D/Compatibility( 5143): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5143): skipping ResolveInfo{1e7fd4af com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5143): considering ResolveInfo{1d9510bc com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5143): default: com.sec.android.app.soundalive.SAControlPanelActivity
,W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 5445): MountEmulatedStorage(),
E/Zygote  ( 5445): v2
I/libpersona( 5445): KNOX_SDCARD checking this for 10055,
I/libpersona( 5445): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5445 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5143): enabling receiver ResolveInfo{30f99845 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SELinux ( 5445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5143): enabling receiver ResolveInfo{31090b9a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5143): enabling receiver ResolveInfo{357f0ccb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5143): enabling receiver ResolveInfo{2d007ca8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5143): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TimaKeyStoreProvider( 5445): TimaSignature is unavailable
D/ActivityThread( 5445): Added TimaKeyStore provider
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1021): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 1021): clearDefaults: com.example.hello
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4883/cgroup.procs: No such file or directory
,D/UserAnalysis.PlaceProvider( 5445): PlaceProvider onCreate()
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 9282(564KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.661ms total 181.741ms
,D/PackageManager( 1021): delete codoeFile: 
,D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1021): UID=10345 Target=com.example.hello
,D/PackageManager( 1021): result of delete: 1{106903618}
,D/AndroidRuntime( 5412): Shutting down VM
D/UserAnalysis.SecureDbManager( 5445): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5445): SecurePlaceDbHelper() 
D/UserAnalysis( 5445): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5445): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5445): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 5180): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 5445): no applications having user consent for prediction
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5462): MountEmulatedStorage()
E/Zygote  ( 5462): v2
I/libpersona( 5462): KNOX_SDCARD checking this for 1000
I/libpersona( 5462): KNOX_SDCARD not a persona
,I/SELinux ( 5462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 5462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,I/ActivityManager( 1021): Killing 4899:com.wssyncmldm/1000 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/TimaKeyStoreProvider( 5462): TimaSignature is unavailable
,D/BluetoothAdapter( 5445): 758430548: getState() :  mService = null. Returning STATE_OFF
,D/ActivityThread( 5462): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 5445): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5445): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ResourcesManager( 5462): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManager( 5462):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1021):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1021): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5219): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,W/ContextImpl( 5219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5219): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5219): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5219): before removeFromFS
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5478): MountEmulatedStorage()
,E/Zygote  ( 5478): v2
I/libpersona( 5478): KNOX_SDCARD checking this for 1000
I/libpersona( 5478): KNOX_SDCARD not a persona
,I/SELinux ( 5478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5478 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/SELinux ( 5478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4899/cgroup.procs: No such file or directory
,E/Zygote  ( 5492): MountEmulatedStorage()
,E/Zygote  ( 5492): v2
I/libpersona( 5492): KNOX_SDCARD checking this for 10095
I/libpersona( 5492): KNOX_SDCARD not a persona
,I/SELinux ( 5492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5492 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/TimaKeyStoreProvider( 5478): TimaSignature is unavailable
,D/ActivityThread( 5478): Added TimaKeyStore provider
E/SELinux ( 5492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5492): TimaSignature is unavailable
,D/ActivityThread( 5492): Added TimaKeyStore provider
,W/art     ( 5412): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ContextImpl( 5478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/PreloadFilterInstaller( 5492): uses FILTER_DB_VER_1,
,E/Zygote  ( 5509): MountEmulatedStorage()
E/Zygote  ( 5509): v2
I/libpersona( 5509): KNOX_SDCARD checking this for 1000
I/libpersona( 5509): KNOX_SDCARD not a persona
,I/SELinux ( 5509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/SQLiteLog( 5492): (284) automatic index on titles(filter_id)
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5509 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 4956:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,E/SQLiteLog( 5492): (284) automatic index on titles(filter_id)
,D/TimaKeyStoreProvider( 5509): TimaSignature is unavailable
,D/ActivityThread( 5509): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 3940:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/FilterUnInstaller( 5219): FilterUninstaller.java : removeFromDB()
,D/FilterProvider( 5492): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 5492): packageName : com.example.hello
,W/ContextImpl( 5219): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,I/ActivityManager( 1021): Killing 4603:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/AcmsPackageEventListener( 5509): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 5509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5526): MountEmulatedStorage()
,E/Zygote  ( 5526): v2
I/libpersona( 5526): KNOX_SDCARD checking this for 1000
I/libpersona( 5526): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Killing 5043:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
I/SELinux ( 5526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AcmsService( 5509): Enter Oncreate
D/AcmsServiceMonitor( 5509): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5509): creating AcmsCore
,D/AcmsCore( 5509): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5509): AcmsCore
,D/AcmsCore( 5509): init
D/AcmsCore( 5509): Looper handler is not null
D/AcmsCore( 5509): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5509): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5509): Incrementing - Counter value: 1
D/AcmsCore( 5509): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5509): onStartCommand
D/AcmsService( 5509): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 5509): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5509): Incrementing - Counter value: 2
D/AcmsService( 5509): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 5509): AcmsCertificateMngr
D/AcmsRevocationMngr( 5509): AcmsRevocationMngr
,D/ActivityThread( 5509): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/SQLiteLog( 5509): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 5526): TimaSignature is unavailable
E/SQLiteDatabase( 5509): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase( 5509): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5509): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
E/SQLiteDatabase( 5509): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:473)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:433)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
E/SQLiteDatabase( 5509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5509): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5509): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5509): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5509): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5509): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 5509): Shutting down VM
D/ActivityThread( 5526): Added TimaKeyStore provider
E/AndroidRuntime( 5509): FATAL EXCEPTION: main
E/AndroidRuntime( 5509): Process: ACMS.Process, PID: 5509
E/AndroidRuntime( 5509): java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@269f648d with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3457)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread$H.handleMessage(ActivityThrea,d.java:1580)
E/AndroidRuntime( 5509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5509): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 5509): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5509): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5509): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 5509): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 5509): Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
E/AndroidRuntime( 5509): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
E/AndroidRuntime( 5509): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
E/AndroidRuntime( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:473)
E/AndroidRuntime( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:433)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
E/AndroidRuntime( 5509): 	... 9 more
E/AndroidRuntime( 5509): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 5509): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/AndroidRuntime( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/AndroidRuntime( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/AndroidRuntime( 5509): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/AndroidRuntime( 5509): 	... 20 more
D/ActivityThread( 5509): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
E/SQLiteLog( 5509): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5509): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase( 5509): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5509): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5509): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 5509): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 5509): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
E/SQLiteDatabase( 5509): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:473)
E/SQLiteDatabase( 5509): 	at android.content.ContentResolver.query(ContentResolver.java:433)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:119)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:129)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
E/SQLiteDatabase( 5509): 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:139)
E/SQLiteDatabase( 5509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5509): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 5509): Sending signal. PID: 5509 SIG: 9
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname ACMS.Process

```
