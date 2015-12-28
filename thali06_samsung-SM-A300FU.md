#### Test 503880191ec81a5_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
--------- beginning of system
V/AlarmManager( 1018): waitForAlarm result :4
D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
I/PowerManagerService( 1018): [PWL] Off : 5s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2037, ws=null) (elapsedTime=47026)
,D/AndroidRuntime( 6020): 
D/AndroidRuntime( 6020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6020): CheckJNI is OFF
D/AndroidRuntime( 6020): readGMSProperty: start
D/AndroidRuntime( 6020): readGMSProperty: already setted!!
D/AndroidRuntime( 6020): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6020): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6020): readGMSProperty: end
D/AndroidRuntime( 6020): addProductProperty: start
E/AffinityControl( 6020): AffinityControl: registerfunction enter
D/AndroidRuntime( 6020): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
E/SMD     (  290): DCD OFF
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6032): MountEmulatedStorage()
E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD checking this for 10346
I/libpersona( 6032): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6032 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1481
D/AndroidRuntime( 6020): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, iello
I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
D/ActivityThread( 6032): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1481): updateVisibility : ActivityRecord{2905642d token=android.os.BinderProxy@8f3b98d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
I/WebViewFactory( 6032): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6032): Time to load native libraries: 2 ms (timestamps 5362-5364)
I/LibraryLoader( 6032): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6032): Binding Chromium to main looper Looper (main, tid 1) {3ebadf7f}
I/LibraryLoader( 6032): Expected native library version number "",actual native library version number ""
I/chromium( 6032): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 6020): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 6032): Initializing chromium process, singleProcess=true
W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6032): ApplicationContext is null in ApplicationStatus
,W/chromium( 6032): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6032): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6032): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6032): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6032): Local Branch: 
I/Adreno-EGL( 6032): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6032): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6032):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6032): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6032): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6032): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6032): CordovaWebView is running on device made by: samsung
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{22f8768a u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 6032): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,W/chromium( 6032): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,V/ActivityThread( 6032): updateVisibility : ActivityRecord{15c07768 token=android.os.BinderProxy@1b6585a {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 6032): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6032): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/InputDispatcher( 1018): Focus entered window: 6032
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6032): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6032): Initialized EGL, version 1.4
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,V/HeadsetService( 2637): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2637): Disconnected process message: 10
,D/OpenGLRenderer( 6032): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6032): Enabling debug mode 0
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1172
I/PowerManagerService( 1018): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1018): Waking up from sleep (uid 10049)...
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): [s] UserActivityState : 0 -> 1
,V/KeyguardServiceDelegate( 1018): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2361610c)
D/KeyguardViewMediator( 1172): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1172): notifyScreenOnLocked
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Display,
D/WindowOrientationListener( 1018): sensor enabled
I/DisplayPowerController( 1018): Blocking screen on until initial contents have been drawn.
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1018): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1018): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1018): !@display_state: OFF -> ON
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SurfaceFlinger(  258): Set power mode=2, type=0 flinger=0xb83ca690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 2 on display: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SensorService( 1018): [SO] activate (ident=0xb87a7168, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,V/ActivityManager( 1018): Display changed displayId=0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{22f8768a u0 com.example.hello/.MainActivity t19}
,D/KeyguardViewMediator( 1172): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1172): onScreenTurnedOn()
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/PalmMotion( 1018): [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/SensorService( 1018): [SO] currT = 86011038000, prevT = 78101442000, diff = 7909596000, [-0.479 -0.038 9.941]
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/NfcService( 1438): call the applyRouting
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/ActivityManager( 1018): Displayed Component not be shown by security: +765ms (total +848ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{22f8768a u0 com.example.hello/.MainActivity t19} time:86033
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
D/BatteryService( 1018): turn off LED
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
E/lights  ( 1018): write_led_info failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
I/SamsungIME( 1785): getCurrentCandidateView
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : -1,
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/SensorService( 1018): [SO] currT = 86081119000, prevT = 78101442000, diff = 7979677000, [-0.479 -0.019 9.922]
D/SensorService( 1018): [SO] -0.479 -0.019 9.922
D/SensorService( 1018): [SO] [100 -> 255]
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1735): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
,V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,E/WifiNative-wlan0( 1018): do suspend false
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBarKeyguardViewManager( 1172): callback.onShown()
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/DisplayPowerController( 1018): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().,
V/KeyguardServiceDelegate( 1018): **** SHOWN CALLED ****
I/DisplayPowerController( 1018): Unblocked screen on after 183 ms
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/DisplayPowerState( 1018): !@ ColorFade exit
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,I/SurfaceFlinger(  258): id=11 Removed DolorFade (9/9)
,I/SurfaceFlinger(  258): id=11 Removed DolorFade (-2/9)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 160 -> 160
E/libEGL  ( 1018): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1018): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1018): lcd : 160 +
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 160 -> 160,
D/lights  ( 1018): lcd : 160 -
D/DisplayPowerController( 1018): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : true
,I/wpa_supplicant( 1375): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1375): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1375): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1375): Scan requested (ret=0) - scan timeout 30 seconds
,D/SamsungIME( 1785): Dismiss ExpandCandiate
,D/BatteryMeterView( 1172): onDraw batteryColor : -1
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 222ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: ON: 222ms
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,W/IInputConnectionWrapper( 6032): showStatusIcon on inactive InputConnection
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1438): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/accuweather( 1563): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/NfcService( 1438): call the applyRouting
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,W/BindingManager( 6032): Cannot call determinedVisibility() - never saw a connection for the pid: 6032
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
I/chromium( 6032): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1563): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,D/accuweather( 1563): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1563): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
I/Timeline( 6032): Timeline: Activity_idle id: android.os.BinderProxy@1b6585a time:86209
I/Timeline( 6032): Timeline: Activity_idle id: android.os.BinderProxy@1b6585a time:86209
,E/accuweather( 1563): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 24
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,D/JsMessageQueue( 6032): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,I/SamsungIME( 1785): KeybaordView init() : load resources
,E/AndroidProtocolHandler( 6032): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SamsungIME( 1785): getCurrentKeyboard
I/SamsungIME( 1785): getTextKeyboard
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(true) while turning screen on: 155ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(true): 157ms
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 379ms
,D/lights  ( 1018): button : 1 +
,D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1785): showDlgMsgBox : false true true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1018): button : 1 -
,I/SamsungIME( 1785): getNextShiftState() cursorCapsMode : 0
,I/SurfaceFlinger(  258): id=12 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=12 Removed iello (-2/8)
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,D/daemonapp( 1602): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1602): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1602): [MSC_Daemon]>>> ====================================================================================================================,
D/comsamsunglog( 1602): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1602): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1602): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1451362980000
D/daemonapp( 1602): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1451341455619
D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1602): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1602): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1602): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1602): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1602): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1602): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/wpa_supplicant( 1375): nl80211: Received scan results (6 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1018): DefaultState{ what=147461 }
,D/jxcore_app_log( 6032): JniHelper::setJavaVM(0xb7e25448), pthread_self() = -1204299248
,D/JX-Cordova( 6032): jxcore cordova android initializing
,E/SQLiteLog( 1803): (10) POSIX Error : 11 SQLite Error : 3850
,W/jxcore-log( 6032): Initializing JXcore engine
W/jxcore-log( 6032): JXcore engine is ready
,W/jxcore-log( 6032): Starting JXcore engine
,E/audit   ( 1833): type=1400 msg=audit(1451341455.890:205): avc:  denied  { ioctl } for  pid=6032 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1833):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1833): type=1300 msg=audit(1451341455.890:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beb41d58 items=0 ppid=308 ppcomm=main pid=6032 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1833): type=1320 msg=audit(1451341455.890:205): 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/jxcore-log( 6032): Platform android
W/jxcore-log( 6032): 
W/jxcore-log( 6032): Process ARCH arm
W/jxcore-log( 6032): 
,I/jxcore-log( 6032): JXcore Cordova bridge is ready!,
I/jxcore-log( 6032): 
W/jxcore-log( 6032): JXcore engine is started
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/jxcore-log( 6032): >> samsung-SM-A300FU
E/jxcore-log( 6032): 
,I/jxcore-log( 6032): Total memory 1451114496
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Free memory 22552576
I/jxcore-log( 6032): 
I/jxcore-log( 6032): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6032): 
I/jxcore-log( 6032): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): userPath [ 'www' ]
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Size 540 960
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Screen Brightness 160
I/jxcore-log( 6032): 
,E/jxcore-log( 6032): Dummy Error Log.
E/jxcore-log( 6032): 
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,I/jxcore-log( 6032): getBuffer is called!!!!
I/jxcore-log( 6032): 
,D/lights  ( 1018): button : 0 +
,D/lights  ( 1018): button : 0 -
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] -0.479 -0.038 9.922
,V/AlarmManager( 1018): waitForAlarm result :4
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6092 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6092): MountEmulatedStorage()
I/libpersona( 6092): KNOX_SDCARD checking this for 10071
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD not a persona,
,I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
,D/ActivityThread( 6092): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6092): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6092): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6092): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6092): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6092): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 48039(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 23MB/35MB, paused 2.067ms total 145.366ms,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1803): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1803): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1803): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1803): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1803): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1803): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1803): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1803): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6092): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6092): Soft error
E/BooksSync( 6092): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6092): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6092): Sync error
E/BooksSync( 6092): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6092): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6092): Finished books sync
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62197, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1018): Killing 5010:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10108/pid_5010/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 6032): disable()
,D/SettingsProvider( 1018): name = bluetooth_on
,D/BluetoothAdapterState( 2637): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2637): Setting state to 13
I/BluetoothAdapterState( 2637): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2637): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2637): updateAdapterState state is 13
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2637): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 2637): Autoconnection is available 
D/BluetoothAdapterService( 2637): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2637): terminating service from this receiver
,D/BluetoothSocket( 2637): close() in, this: android.bluetooth.BluetoothSocket@79ba33f, channel: 19, state: LISTENING
D/BluetoothSocket( 2637): close() this: android.bluetooth.BluetoothSocket@79ba33f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4d0b247, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2abbe40cmSocket: android.net.LocalSocket@1ec3f155 impl:android.net.LocalSocketImpl@9b3d76a fd:FileDescriptor[74]
,D/BluetoothSocket( 2637): Closing mSocket: android.net.LocalSocket@1ec3f155 impl:android.net.LocalSocketImpl@9b3d76a fd:FileDescriptor[74]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2637): onBluetoothDisable()
,D/BluetoothAdapterProperties( 2637): mDiscovering is false
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2637): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/WifiService( 1018): setWifiEnabled: false pid=6032, uid=10346
,D/SettingsProvider( 1018): name = wifi_on
W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =13
,D/BluetoothTile( 1172):  onBluetoothStateChange:,
,I/jxcore-log( 6032): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 6032): 
D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1172):  getBluetoothState : 13
,I/jxcore-log( 6032): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6032): 
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1375): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1375): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1375): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1375): Scan requested (ret=0) - scan timeout 30 seconds
V/BluetoothEventManager( 1307): Received android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 1785): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1172):  handleUpdatestate:false name:null
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothAdapterProperties( 2637): Scan Mode:20
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false,
D/BluetoothAdapterState( 2637): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2637): btif_dm_generic_evt: event=33036
D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
E/bt-btif ( 2637): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 2637): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 2637): cmd socket is not created
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Bluetooth
,E/bt-btm  ( 2637): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2637): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 2637): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothSocket( 2637): close() in, this: android.bluetooth.BluetoothSocket@3331345b, channel: 5, state: LISTENING
D/BluetoothSocket( 2637): close() this: android.bluetooth.BluetoothSocket@3331345b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d17ba74, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@234934f8mSocket: android.net.LocalSocket@41f4dd1 impl:android.net.LocalSocketImpl@bb00036 fd:FileDescriptor[76]
D/BluetoothSocket( 2637): Closing mSocket: android.net.LocalSocket@41f4dd1 impl:android.net.LocalSocketImpl@bb00036 fd:FileDescriptor[76]
,I/BtOppRfcommListener( 2637): stopping Accept Thread
D/BluetoothSocket( 2637): close() in, this: android.bluetooth.BluetoothSocket@39c4bb37, channel: 12, state: LISTENING
D/BluetoothSocket( 2637): close() this: android.bluetooth.BluetoothSocket@39c4bb37, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2640e35e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d58a8a4mSocket: android.net.LocalSocket@4f9f60d impl:android.net.LocalSocketImpl@2273e9c2 fd:FileDescriptor[80]
W/bt-l2cap( 2637): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothSocket( 2637): Closing mSocket: android.net.LocalSocket@4f9f60d impl:android.net.LocalSocketImpl@2273e9c2 fd:FileDescriptor[80]
W/bt-l2cap( 2637): L2CAP - PSM: 0x001b not found for deregistration
,I/BtOppRfcommListener( 2637): BluetoothSocket listen thread finished
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,V/BluetoothOppManager( 2637): cleanUp...
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/BluetoothPbap( 1307): Proxy object disconnected
D/PbapServerProfile( 1307): Bluetooth service disconnected
,V/NativeCrypto( 1803): Read error: ssl=0xb82e8528: I/O error during system call, Connection timed out
,V/NativeCrypto( 1803): SSL shutdown failed: ssl=0xb82e8528: I/O error during system call, Broken pipe
,E/ConnectivityService( 1018): updateNetworkInfo()
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1018): Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,I/qtaguid ( 1018): Untagging socket 348
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1018): InactiveState{ what=131204 }
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1018): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: FAILED
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 1
D/RttService( 1018): SCAN_AVAILABLE : 1
D/WifiScanningService( 1018): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1018): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 1018): P2pDisablingState
,D/WifiP2pService( 1018): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 1018): p2p socket connection lost
,D/WifiP2pService( 1018): P2pDisabledState
,D/WifiP2pService( 1018): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1018): DefaultState{ what=143375 }
V/BluetoothStatusReceiver( 1172): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1172): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1018): onP2pDisconnected
E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer,
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1018): disconnect,
D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Zygote  ( 6134): MountEmulatedStorage()
,E/Zygote  ( 6134): v2
I/libpersona( 6134): KNOX_SDCARD checking this for 10055
I/libpersona( 6134): KNOX_SDCARD not a persona,
,I/SELinux ( 6134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
I/SELinux ( 6134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1450): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1450): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6134 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 9ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AllShareCastTile( 1172): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1172): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/wpa_supplicant( 1375): p2p0: State: DISCONNECTED -> DISCONNECTED
D/TimaKeyStoreProvider( 6134): TimaSignature is unavailable
D/ActivityThread( 6134): Added TimaKeyStore provider
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
D/HotspotTile( 1172): onReceive : 0, 0
D/WifiCredService( 1307): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/UserAnalysis.PlaceProvider( 6134): PlaceProvider onCreate(),
W/bt-l2cap( 2637): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2637): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x001b not found for deregistration,
W/bt-l2cap( 2637): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2637): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2637): ag scb idx 1 not allocated
,W/bt-btif ( 2637): ag scb idx 2 not allocated
E/bt-btif ( 2637): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2637): exiting userial_read_thread
D/bt_userial_mct( 2637): Leaving userial_evt_read_thread()
,D/bt_userial_mct( 2637): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2637): hw_epilog_process
D/bt_userial_mct( 2637): userial_close
I/bt_vendor( 2637): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/UserAnalysis.SecureDbManager( 6134): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6134): SecurePlaceDbHelper() 
D/UserAnalysis( 6134): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6134): onCreate()
,I/ActivityManager( 1018): Killing 5319:com.google.android.gm/u0a99 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6134): no applications having user consent for prediction
,D/AuthorizationBluetoothService( 1803): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/PlaceDetection v1.0.19 ( 6134): [PlaceDetection::stopService] Service stopped.
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/PlaceDetection v1.0.19 ( 6134): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/Hs20UtilService( 1647): Starting #8
I/Hs20UtilService( 1647): Message received 5007
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3,
I/wpa_supplicant( 1375): Blacklist: Clear (all) 
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
D/AndroidRuntime( 6131): 
D/AndroidRuntime( 6131): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/AndroidRuntime( 6131): CheckJNI is OFF
,D/AndroidRuntime( 6131): readGMSProperty: start
D/AndroidRuntime( 6131): readGMSProperty: already setted!!
D/AndroidRuntime( 6131): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6131): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6131): readGMSProperty: end
D/AndroidRuntime( 6131): addProductProperty: start
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,E/Zygote  ( 6168): MountEmulatedStorage()
E/Zygote  ( 6168): v2
I/libpersona( 6168): KNOX_SDCARD checking this for 10064
I/libpersona( 6168): KNOX_SDCARD not a persona
I/SELinux ( 6168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6168 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/wpa_supplicant( 1375): p2p0: CTRL-EVENT-TERMINATING 
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
E/SELinux ( 6168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,D/TimaKeyStoreProvider( 6168): TimaSignature is unavailable,
D/ActivityThread( 6168): Added TimaKeyStore provider
I/wpa_supplicant( 1375): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1375): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1375): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48,
I/wpa_supplicant( 1375): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1375): wlan0: State: DISCONNECTED -> DISCONNECTED,
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): InitialState.processMessage what=4
E/Tethering( 1018): No numeric data
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
,V/NetworkStats( 1018): performPollLocked() took 5ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ResourcesManager( 6168): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
,D/FileShare-Client( 6168): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 6168): ClientBroadcastReceiver.onReceive - disconnected
,I/bt_vendor( 2637): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2637): bluetooth satus is on
I/bt_vendor( 2637): bt-vendor : resetting BT status
I/bt_vendor( 2637): Starting hciattach daemon
I/bt_vendor( 2637): try to set false
,I/bt_vendor( 2637): Starting hciattach daemon
I/bt_vendor( 2637): try to set false,
,I/bt_vendor( 2637): cleanup
I/GKI_LINUX( 2637): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2637): GKI_exit_task 0 done
I/GKI_LINUX( 2637): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2637): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2637): isSecureModeOn:false
D/BluetoothAdapterService( 2637): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.gatt.GattService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2637): handleDebugAction() action=null
W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2637): Received stop request...Stopping profile...
D/BtGatt.GattService( 2637): stop()
D/BtGatt.AdvertiseManager( 2637): advertise clients cleared
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/libprocessgroup( 1018): failed to open /acct/uid_10099/pid_5319/cgroup.procs: No such file or directory
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.a2dp.A2dpService
D/FileShare-Client( 6168): Outbound.stopDelayTimer - 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/AffinityControl( 6131): AffinityControl: registerfunction enter
E/Zygote  ( 6190): MountEmulatedStorage()
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD checking this for 10065
I/libpersona( 6190): KNOX_SDCARD not a persona
I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6190 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5224:com.google.android.talk/u0a102 (adj 15): empty #31
D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 2637): Received stop request...Stopping profile...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
D/HeadsetProfile( 1307): Bluetooth service disconnected
W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.pan.PanService
,D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2637): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2637): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2637): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2637): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2637): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2637): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2637): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2637): Stopping profile services that were post enabled
E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/AndroidRuntime( 6131): Calling main entry com.android.commands.pm.Pm
D/A2dpService( 2637): Received stop request...Stopping profile...
D/A2dpStateMachine( 2637): Exit Disconnected: -1
,D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
,D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
D/ActivityThread( 6190): Added TimaKeyStore provider
D/BluetoothA2dp( 1018): Proxy object disconnected
D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 2637): Received stop request...Stopping profile...
D/HidService( 2637): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2637): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2637): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2637): Cleaning up Bluetooth GID callback object
,D/BluetoothA2dp( 1307): Proxy object disconnected
,D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
D/A2dpProfile( 1307): Bluetooth service disconnected
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{103009435}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/HealthService( 2637): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
D/BluetoothInputDevice( 1307): Proxy object disconnected
D/HidProfile( 1307): Bluetooth service disconnected
,E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2637): Profile still running: com.android.bluetooth.hid.HidService
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
,W/BluetoothHeadsetServiceJni( 2637): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2637): Cleaning up Bluetooth Handsfree callback object
D/PanService( 2637): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
,D/BluetoothPan( 1018): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 1307): BluetoothPAN Proxy object disconnected
D/PanProfile( 1307): Bluetooth service disconnected
,D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/BluetoothMapService( 2637): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
,D/SapService( 2637): Received stop request...Stopping profile...
D/SapService( 2637): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2637): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25522795
,E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2637): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2637): Proxy object disconnected
D/BluetoothAdapterService( 2637): Bluetooth A2dp source service disconnected
D/BluetoothMap( 1307): Proxy object disconnected
,D/MapProfile( 1307): Bluetooth service disconnected
I/GKI_LINUX( 2637): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2637): GKI_exit_task 2 done
I/GKI_LINUX( 2637): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2637): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/FileShare-Server( 6190): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothAdapterService( 2637): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2637): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2637): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2637): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/Bluetoothsap( 1307): BluetoothSAP Proxy object disconnected
D/SapProfile( 1307): Bluetooth service disconnected
W/BluetoothPanServiceJni( 2637): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 2637): Cleaning up Bluetooth PAN callback object
,D/PackageManager( 1018): !@killApplicatoin: 10346, uninstall pkg
,I/wpa_supplicant( 1375): Blacklist: Clear (all) 
E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2637): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2637): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(626141077)( 2637): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2637): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2637): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 2637): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2637): Setting state to 10
I/BluetoothAdapterState( 2637): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2637): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2637): updateAdapterState state is 10
,D/BluetoothAdapterService( 2637): Autoconnection is available 
D/BluetoothAdapterService( 2637): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2637): Entering OffState
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1018): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6207): MountEmulatedStorage()
,I/libpersona( 6207): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6207): v2
I/libpersona( 6207): KNOX_SDCARD not a persona
I/SELinux ( 6207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/BluetoothAdapter( 2637): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2637): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1430): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1430): Bluetooth is turned off, stop adv and scan
,I/SELinux ( 6207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6207 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 6207): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4194:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 6032:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,D/TimaKeyStoreProvider( 6207): TimaSignature is unavailable
,D/ActivityThread( 6207): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10102/pid_5224/cgroup.procs: No such file or directory
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false,
I/wpa_supplicant( 1375): wlan0: CTRL-EVENT-TERMINATING ,
,W/PackageSettings( 1018): Skipping PackageSetting{3f407157 com.test.thalitest/10338} due to missing metadata
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,W/ActivityManager( 1018): Force removing ActivityRecord{22f8768a u0 com.example.hello/.MainActivity t19}: app died, no saved state
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6032
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/7)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/ActivityManager( 1018): Display changed displayId=0
,D/Launcher( 1481): onRestart, Launcher: 100313105
,D/BluetoothA2dp( 2637): onBluetoothStateChange: up=false
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10346 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/Launcher( 1481): onStart, Launcher: 100313105
D/Launcher.HomeView( 1481): onStart
,D/Launcher( 1481): onResume, Launcher: 100313105
,W/ResourcesManager( 6207): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/art     ( 3966): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 688us total 22.280ms
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,D/BluetoothMap( 1307): onBluetoothStateChange: up=false
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1481): onResume
I/art     ( 5362): Explicit concurrent mark sweep GC freed 11498(827KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 734us total 41.633ms
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1785): mOCRHelper is null
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1307): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1307): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1307): Bluetooth is turned off, stop adv and scan
,D/BluetoothInputDevice( 1307): onBluetoothStateChange: up=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1307): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapter( 1438): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1438): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1735): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1735): Bluetooth is turned off, stop adv and scan
,W/Settings( 1735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HotspotTile( 1172): onReceive : 1, 0
,E/BluetoothManagerService( 1018): Unable to call onBluetoothStateChange() on callback #14
E/BluetoothManagerService( 1018): android.os.DeadObjectException
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1018): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/MenuAppsGridFragment( 1481): onResume
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4194/cgroup.procs: No such file or directory
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/SurfaceFlinger(  258): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/BluetoothPbap( 1307): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1450): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1450): Bluetooth is turned off, stop adv and scan
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/BluetoothAdapter( 1172): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1172): Bluetooth is turned off, stop adv and scan
,D/Bluetoothsap( 1307): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1307): Unbinding service...
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1018): Focus entered window: 1481
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/GKI_LINUX( 2637): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2637): GKI_exit_task 1 done
,I/GKI_LINUX( 2637): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2637): cleanupNative: return from cleanup
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/BluetoothAdapter( 1172): 236154092: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1172): 236154092: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1172):  getBluetoothState : 10
,D/BluetoothAdapter( 1172): 236154092: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1172): 236154092: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1172): 236154092: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1307): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/RegisteredServicesCache( 1438): empty dynamic service
,I/SamsungIME( 1785): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/art     ( 2637): System.exit called, status: 0
,I/AndroidRuntime( 2637): VM exiting with result code 0, cleanup skipped.
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 6032 uid 10346
,I/ActivityManager( 1018): Process com.android.bluetooth (pid 2637)(adj 0) has died(74,687)
,D/SamsungIME( 1785): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/ActivityManager( 1018): Displayed Component not be shown by security: +340ms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 44500(2MB) AllocSpace objects, 7(164KB) LOS objects, 33% free, 23MB/35MB, paused 7ms total 296.913ms
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
,I/AASA_removePackage( 1018): UID=10346 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{103009435}
,D/AndroidRuntime( 6131): Shutting down VM
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Babel_SMS( 6207): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6207): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6207): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6207): MmsConfig.loadFromDatabase
,W/art     ( 6207): Suspending all threads took: 8.164ms
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
E/Babel_SMS( 6207): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6207): MmsConfig.loadFromResources
E/Babel_SMS( 6207): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6207): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Settings( 6207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/Babel_Crash( 6207): startup - clean
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Tethering( 1018): interfaceRemoved wlan0
E/Tethering( 1018): attempting to remove unknown iface (wlan0), ignoring
,W/art     ( 6131): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Babel   ( 6207): deleted: false for 0
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/art     ( 6207): Suspending all threads took: 11.432ms
,D/Tethering( 1018): interfaceRemoved p2p0
E/Tethering( 1018): attempting to remove unknown iface (p2p0), ignoring
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@8f3b98d time:93347
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10346
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10346
D/TaskPersister( 1018): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1018): [SO] activate (ident=0xb87a7168, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb85dd330, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1647): Starting #9
,I/Hs20UtilService( 1647): Message received 5007
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =10
I/InputMethodManagerService( 1018): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6207): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6207): Unsupported mime audio/evrc
,W/AudioCapabilities( 6207): Unsupported mime audio/qcelp
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{373a5a02 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:93440
,W/System.err( 1018): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1018): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 1018): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
,W/System.err( 1018): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at com.android.server.SystemServer.run(SystemServer.java:444)
W/System.err( 1018): 	at com.android.server.SystemServer.main(SystemServer.java:328)
W/AudioCapabilities( 6207): Unsupported mime audio/mpeg-L1
W/System.err( 1018): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1018): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 12 more
,W/AudioCapabilities( 6207): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1647): Starting #10
,I/Hs20UtilService( 1647): Message received 5011
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 6207): Unsupported mime audio/x-ms-wma
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 6207): Unsupported mime audio/x-ima,
,W/AudioCapabilities( 6207): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6207): Unsupported mime audio/evrc
,E/Zygote  ( 6239): MountEmulatedStorage()
I/libpersona( 6239): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 6239): v2
I/libpersona( 6239): KNOX_SDCARD not a persona
,I/SELinux ( 6239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6239 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,W/VideoCapabilities( 6207): Unsupported mime video/wvc1,
W/VideoCapabilities( 6207): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6207): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6207): Unsupported mime video/wvc1
,W/VideoCapabilities( 6207): Unsupported mime video/x-ms-wmv
,D/TimaKeyStoreProvider( 6239): TimaSignature is unavailable
,D/ActivityThread( 6239): Added TimaKeyStore provider
W/VideoCapabilities( 6207): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6207): Unsupported mime video/x-ms-wmv8,
,W/VideoCapabilities( 6207): Unsupported mime video/mp43
,W/VideoCapabilities( 6207): Unsupported mime video/sorenson
,W/VideoCapabilities( 6207): Unsupported mime video/mp4v-esdp

```
