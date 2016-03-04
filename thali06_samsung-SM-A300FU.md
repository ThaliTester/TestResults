#### Test 6177688874f8189_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 5356): 
D/AndroidRuntime( 5356): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5356): CheckJNI is OFF
D/AndroidRuntime( 5356): readGMSProperty: start
D/AndroidRuntime( 5356): readGMSProperty: already setted!!
D/AndroidRuntime( 5356): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5356): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5356): readGMSProperty: end
D/AndroidRuntime( 5356): addProductProperty: start
E/AffinityControl( 5356): AffinityControl: registerfunction enter
D/AndroidRuntime( 5356): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
D/Launcher.HomeView( 1479): onPause
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1479
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 5356): Shutting down VM
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
V/TaskCloserActivity( 4934): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : -2122120936
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 5368): MountEmulatedStorage()
E/Zygote  ( 5368): v2
I/libpersona( 5368): KNOX_SDCARD checking this for 10338
I/libpersona( 5368): KNOX_SDCARD not a persona
I/SELinux ( 5368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5368 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5368): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1eee9064 token=android.os.BinderProxy@3d9d569d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 5368): TimaSignature is unavailable
D/ActivityThread( 5368): Added TimaKeyStore provider
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/ActivityManager( 1021): Display changed displayId=0
D/Launcher.HomeView( 1479): onStop
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1eee9064 token=android.os.BinderProxy@3d9d569d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1021): [SO] activate (ident=0xb789d710, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1021): unregisterListener ::   
I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1021): [SO] changed settle time [1]
D/SensorService( 1021): [SO] setDelay [66000000]
D/SensorService( 1021): [SO] activate (ident=0xb7a73ee8, enabled=1)
D/SensorService( 1021): [SO] AR_init
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/Launcher( 1479): onTrimMemory. Level: 20
D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 5356): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 5368): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5368): Time to load native libraries: 2 ms (timestamps 4063-4065)
,I/LibraryLoader( 5368): Expected native library version number "",actual native library version number ""
,D/SensorService( 1021): [SO] currT = 104071056000, prevT = 103711057000, diff = 359999000, [-0.326 -0.038 9.922]
,D/SensorService( 1021): [SO] -0.326 -0.038 9.922
D/SensorService( 1021): [SO] [100 -> 255]
,V/WebViewChromiumFactoryProvider( 5368): Binding Chromium to main looper Looper (main, tid 1) {24c1c03b}
,I/LibraryLoader( 5368): Expected native library version number "",actual native library version number ""
,I/chromium( 5368): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5368): Initializing chromium process, singleProcess=true
,W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5368): ApplicationContext is null in ApplicationStatus
,W/chromium( 5368): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5368): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5368): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5368): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5368): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5368): Local Branch: 
I/Adreno-EGL( 5368): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5368): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5368):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5368): 781918957: getState() :  mService = null. Returning STATE_OFF
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5368): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5368): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5368): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 5368): CordovaWebView is running on device made by: samsung
,W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5368): Render dirty regions requested: true
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,W/chromium( 5368): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5368): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5368): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1021): Focus entered window: 5368
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5368): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5368): Initialized EGL, version 1.4
D/OpenGLRenderer( 5368): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5368): Enabling debug mode 0
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1021): Displayed Component not be shown by security: +805ms
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1021): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,W/ActivityManager( 1021): mDVFSHelper.release()
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{32d8e4ff u0 com.test.thalitest/.MainActivity t22} time:104625
,I/Timeline( 5368): Timeline: Activity_idle id: android.os.BinderProxy@6a83ad2 time:104636
,I/SamsungIME( 1803): getCurrentCandidateView
,D/SamsungIME( 1803): Dismiss ExpandCandiate
,W/BindingManager( 5368): Cannot call determinedVisibility() - never saw a connection for the pid: 5368
,I/SamsungIME( 1803): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1803): getDebugLevel  : 0x4f4c
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (7/8)
,I/SamsungIME( 1803): KeybaordView init() : load resources
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (-2/8)
,I/SamsungIME( 1803): getCurrentKeyboard
I/SamsungIME( 1803): getTextKeyboard
,D/SamsungIME( 1803): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,D/JsMessageQueue( 5368): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5368): JniHelper::setJavaVM(0xb6ffa448), pthread_self() = -1219173312
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5368): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37b027c9 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ece4fc added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5368): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5368): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5368): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5368): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5368): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5368): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5368): Background sticky concurrent mark sweep GC freed 15767(1947KB) AllocSpace objects, 0(0B) LOS objects, 2% free, 13MB/13MB, paused 12.513ms total 33.671ms
,D/PowerManagerService( 1021): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1021): Nap time (uid 1000)...
D/PowerManagerService( 1021): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1021): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1021): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService( 1021): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 1021): WindowOrientationListener disabled
D/SensorService( 1021): [SO] activate (ident=0xb7a73ee8, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1021): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1021): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1021): handleSandman : startDream(true)
E/PowerManagerService( 1021): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1021): Sleeping (uid 1000)...
D/PowerManagerService( 1021): [s] UserActivityState : 4 -> 0
I/SurfaceFlinger(  259): id=13 createSurf (540x960),-1 flag=20004, DolorFade
,D/SensorManager( 1021): unregisterListener ::   
,D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/KeyguardViewMediator( 1181): timeout : 5000
,D/PowerManagerService( 1021): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 21ms
,D/DisplayPowerController( 1021): ColorFade: onAnimationStart
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
,D/VolumePanel( 1181): onScreenTurnedOff()
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
,D/LightsService( 1021): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1021) 
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOff
D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1021): turn on LED for fully charged
,D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1021): write_int failed to open -1
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1021): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1021): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1021): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1021): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1021): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1021): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1021): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1021): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1021): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1021): fail to set sysfs 0
W/System.err( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1021): 	... 10 more
,V/ActivityThread( 5368): updateVisibility : ActivityRecord{3cae3c7f token=android.os.BinderProxy@6a83ad2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/MotionRecognitionService( 1021):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1021):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1021): startHal
,D/NotificationService( 1021): ACTION_SCREEN_OFF
E/wifi    ( 1021): getStaticLongField sWifiHalHandle 0x9d8d27fc
I/WifiNative-HAL( 1021): Could not start hal
W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/LightsService( 1021): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 1021) 
D/LightsService( 1021): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService( 1021): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1021): write_int failed to open -1
D/LightsService( 1021): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
,V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1021): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1021): Bridge Server is not available
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1401): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1021): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1021): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1441): call the applyRouting
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,D/accuweather( 1572): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1572): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1619): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1572): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1572): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1619): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1834): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1619): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1572): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/DisplayPowerState( 1021): !@ ColorFade entry
D/DisplayPowerController( 1021): ColorFade: onAnimationEnd
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4295, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/SSRM:n  ( 1021): SIOP:: AP = 310
D/lights  ( 1021): lcd : 0 +
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/accuweather( 1572): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/lights  ( 1021): lcd : 0 -
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1021): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1021): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/accuweather( 1572): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1572): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1021): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1021): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 1021): Excessive delay in MISC setInteractive(false) while turning screen off: 62ms
I/QCOM PowerHAL( 1021): Got set_interactive hint
,D/PowerManagerService( 1021): Excessive delay in nativeSetInteractive(false): 64ms
,D/DisplayManagerService( 1021): !@display_state: ON -> OFF
,I/DisplayManagerService( 1021): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1021): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb7737690
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb87c27c8
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1199823560)
,E/SMD     (  290): DCD OFF
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1199823560) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
,I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb87c27c8,
,W/jxcore-log( 5368): Initializing JXcore engine
W/jxcore-log( 5368): JXcore engine is ready
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl( 1021): Excessive delay in setPowerMode(): 245ms
D/PowerManagerService( 1021): Excessive delay in !@display_state: OFF: 252ms
I/libsuspend( 1021): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1021): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 317ms
I/libsuspend( 1021): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1021): [PWL] Off : 0s ago
,E/audit   ( 1800): type=1400 msg=audit(1457130176.550:203): avc:  denied  { ioctl } for  pid=5419 comm="Thread-919" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1800):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1800): type=1300 msg=audit(1457130176.550:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9c2348f8 items=0 ppid=306 ppcomm=main pid=5419 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-919" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1800): type=1320 msg=audit(1457130176.550:203): 
,W/jxcore-log( 5368): Starting JXcore engine
,W/jxcore-log( 5368): Platform android
W/jxcore-log( 5368): 
,W/jxcore-log( 5368): Process ARCH arm
W/jxcore-log( 5368): 
,D/FactoryTest( 4651): Not factory mode
,D/FactoryTest( 4651): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4651): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4651): still no open session command from host, so toast
,W/ContextImpl( 4651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4651): Timeline: Activity_launch_request id:com.android.settings time:106978
,E/PersonaManagerService( 1021): inState():  stateMachine is null !!
,I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/ActivityManager( 1021): Display changed displayId=0
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 5368
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 4651): started activity for popup
,W/ResourcesManager( 4651): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4651): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4651): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4651): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4651): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4651): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus entered window: 5368
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1021): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3b5fb948 attribute=android.view.inputmethod.EditorInfo@7e603e1, token = android.os.BinderProxy@11c59a18
,D/SettingsReceiverActivity( 4651): dev.kiessupport is : TRUE
,D/PhoneWindow( 4651): *FMB* installDecor mIsFloating : true
,I/jxcore-log( 5368): JXcore Cordova bridge is ready!
I/jxcore-log( 5368): 
D/PhoneWindow( 4651): *FMB* installDecor flags : 8388610
W/jxcore-log( 5368): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5368): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5368): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5368): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,V/ActivityThread( 5368): updateVisibility : ActivityRecord{3cae3c7f token=android.os.BinderProxy@6a83ad2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5368): Timeline: Activity_idle id: android.os.BinderProxy@6a83ad2 time:107189
,I/chromium( 5368): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/ActivityManager( 1021): Task #22 is topTask exclude finishing tasks.com.android.server.am.ActivityStack.adjustFocusedActivityLocked:3569 com.android.server.am.ActivityStack.finishActivityLocked:3855 com.android.server.am.ActivityStack.requestFinishActivityLocked:3667 com.android.server.am.ActivityManagerService.finishActivity:6360 android.app.ActivityManagerNative.onTransact:328 
,D/FocusedStackFrame( 1021): Set to : 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus left window: 5368
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1021): Killing 4912:com.wssyncmldm/1000 (adj 15): empty #31
,W/PluginManager( 5368): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{32d8e4ff u0 com.test.thalitest/.MainActivity t22 f}
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1479): onRestart, Launcher: 16917783
,D/Launcher( 1479): onStart, Launcher: 16917783
,D/Launcher.HomeView( 1479): onStart
,V/ActivityThread( 1479): updateVisibility : ActivityRecord{1eee9064 token=android.os.BinderProxy@3d9d569d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1479): onStop
D/Launcher( 1479): onRestart, Launcher: 16917783
,D/Launcher( 1479): onStart, Launcher: 16917783
,D/Launcher.HomeView( 1479): onStart
D/Launcher( 1479): onResume, Launcher: 16917783
,D/SettingsProvider( 1021): name = kids_home_mode
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/Launcher.HomeView( 1479): onResume
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/MenuAppsGridFragment( 1479): onResume
,W/BindingManager( 5368): Cannot call determinedVisibility() - never saw a connection for the pid: 5368
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1021): handle home activity for 0
,I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1021): post home show event for user 0
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
,D/Launcher.HomeView( 1479): onPause
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,I/splitIntent( 1021): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1021): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4379): Receive : home resume,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2402): onReceive by home
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,I/SurfaceFlinger(  259): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/TaskCloserActivity( 4934): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/Mms/UIEventReceiver( 4216): ui event
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/InputDispatcher( 1021): Focus entered window: 1479
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1479): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,V/ActivityThread( 1479): updateVisibility : ActivityRecord{1eee9064 token=android.os.BinderProxy@3d9d569d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1479): onStop
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/IInputConnectionWrapper( 5368): showStatusIcon on inactive InputConnection
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1021): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SamsungIME( 1803): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/PersonaManager( 1021): isKioskContainerExistOnDevice
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
I/splitIntent( 1021): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@3d9d569d time:107350
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 4934): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1021): mDVFSHelper.release()
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{17ce496 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:107374
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4912/cgroup.procs: No such file or directory
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/Watchdog( 1021): !@Sync 3
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager( 1021): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off,
,V/KeyguardEffectViewController( 1181): *** Keyguard wallpaper service already unbounded
,V/AlarmManagerEXT( 1021): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1021): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate,
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerManagerService( 1021): [PWL] Off : 5s ago
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/SSRM:n  ( 1021): SIOP:: AP = 300
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 15s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/SSRM:n  ( 1021): SIOP:: AP = 270
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 30s ago,
,E/Watchdog( 1021): !@Sync 4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1021): waitForAlarm result :4
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10011
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,I/PowerManagerService( 1021): [PWL] Off : 50s ago
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 5,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4769): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 75s ago,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1021): waitForAlarm result :8,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1021): !@Sync 7
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/art     ( 1181): Background sticky concurrent mark sweep GC freed 11281(512KB) AllocSpace objects, 0(0B) LOS objects, 3% free, 15MB/16MB, paused 8.321ms total 23.761ms
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 8,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 180s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 9,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1021): initializing...,
I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 10
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 225s ago,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 11
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4769): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4769): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4769): Ignoring header User-Agent because its value was null.
I/System.out( 4769): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10026
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 12,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 275s ago,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1021): !@Sync 13,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 14,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 15
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  314): bootchecker wake up!!,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 390s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 16
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 17,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8,
V/AlarmManager( 1021): No more alarm at this time.nowELAPSED=529954 batch.start=797956
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 455s ago
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  318): Stop the daemon....,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 19,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 20,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 525s ago,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 21,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 56515(5MB) AllocSpace objects, 228(3MB) LOS objects, 33% free, 23MB/35MB, paused 2.403ms total 154.810ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4769): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4769): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4769): Ignoring header User-Agent because its value was null.
I/System.out( 4769): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10026
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 22,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 600s ago,
,E/Watchdog( 1021): !@Sync 23,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 24
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 25,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 680s ago,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/Finsky  ( 4769): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Finsky  ( 4769): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog( 1021): !@Sync 26
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4769): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4769): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4769): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4769): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4769): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1659): client connected with version: 7571000
,D/Finsky  ( 4769): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 27
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 28,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 35129(2MB) AllocSpace objects, 5(101KB) LOS objects, 39% free, 7MB/12MB, paused 1.146ms total 51.104ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 29
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4769): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4769): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 30,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 31
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 39121(3MB) AllocSpace objects, 119(1909KB) LOS objects, 33% free, 23MB/35MB, paused 2.319ms total 145.212ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,E/PlayEventLogger( 4769): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4769): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4769): Ignoring header User-Agent because its value was null.
I/System.out( 4769): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10026
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/PowerManagerService( 1021): [PWL] Off : 855s ago
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 32,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 33,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 34,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 950s ago
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 35
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 36
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 37,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 38,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 39,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1021): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1021): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1021): Updating Usage Statistics in DB @ 1457131285889
,I/ApplicationUsage( 1021): Done Updating Usage Statistics in DB @ 1457131285893
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 40,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 41,
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
E/PlayEventLogger( 4769): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4769): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4769): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4769): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4769): Ignoring header User-Agent because its value was null.
I/System.out( 4769): (HTTPLog)-Static: isSBSettingEnabled false
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10026
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/PowerManagerService( 1021): [PWL] Off : 1155s ago
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 42,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 43
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5950): 
D/AndroidRuntime( 5950): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5950): CheckJNI is OFF
D/AndroidRuntime( 5950): readGMSProperty: start
D/AndroidRuntime( 5950): readGMSProperty: already setted!!
D/AndroidRuntime( 5950): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5950): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5950): readGMSProperty: end
D/AndroidRuntime( 5950): addProductProperty: start
E/AffinityControl( 5950): AffinityControl: registerfunction enter
D/AndroidRuntime( 5950): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{663068300}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1021): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 5368:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1021): Skipping PackageSetting{3ee29882 com.example.hello/10346} due to missing metadata
W/ActivityManager( 1021): Spurious death for ProcessRecord{367b59d5 5368:com.test.thalitest/u0a338}, curProc for 5368: null
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3684): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 832us total 37.531ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1803): mOCRHelper is null
W/GeofencerStateMachine( 1659): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3449): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 04 23:43:04 GMT+01:00 2016
I/art     ( 4130): Explicit concurrent mark sweep GC freed 19904(1260KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.096ms total 93.460ms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3449): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5963): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5963 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 5963): v2
I/libpersona( 5963): KNOX_SDCARD checking this for 10090
I/libpersona( 5963): KNOX_SDCARD not a persona
I/SELinux ( 5963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3449): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 3449): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 5963): TimaSignature is unavailable
D/ActivityThread( 5963): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RegisteredServicesCache( 1441): empty dynamic service
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
I/art     ( 1021): Explicit concurrent mark sweep GC freed 28274(3MB) AllocSpace objects, 158(2MB) LOS objects, 33% free, 23MB/35MB, paused 2.591ms total 223.976ms
I/art     ( 1021): WaitForGcToComplete blocked for 160.403ms for cause Explicit
D/elm:15121( 5963): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 5963): ELMEngine.ELMEngine( context ).
D/elm:15121( 5963): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 5963): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 5963): ElmAgentService : onCreate()
D/RCPManagerService( 1021): PackageReceiver onReceive()
D/elm:15121( 5963): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 5963): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5963): MDMBridge.getInstance()
D/elm:15121( 5963): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 5963): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3449): KLMSIntentService(): onDestroy()
D/elm:15121( 5963): ElmAgentService : onDestroy().
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1021): removeObsoleteFile: deleting file=22_task.xml
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 5071): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5071): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5071): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5071): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5179): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5179): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/art     ( 1021): Explicit concurrent mark sweep GC freed 12848(622KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 11.350ms total 193.077ms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4379): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 4216): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/FreeMessageReceiverService( 4216): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist( 1021): enable value -1
I/TactileAssist( 1021): internal enable value -1
I/TactileAssist( 1021): intensity value -1
I/TactileAssist( 1021): saveAppList value true
D/Mms/FreeMessageReceiverService( 4216): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1021): List of disabled apps :
W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/Compatibility( 5119): onReceive() it will make start service
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5119): onHandleIntent()
D/Compatibility( 5119): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5119): found: 2
D/Compatibility( 5119): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5119): skipping ResolveInfo{104d6cb1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5119): considering ResolveInfo{9fb6596 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5119): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5119): enabling receiver ResolveInfo{1022517 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 5983): MountEmulatedStorage()
E/Zygote  ( 5983): v2
I/libpersona( 5983): KNOX_SDCARD checking this for 10055
I/libpersona( 5983): KNOX_SDCARD not a persona
I/SELinux ( 5983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5983 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/Compatibility( 5119): enabling receiver ResolveInfo{1c00fd04 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Compatibility( 5119): enabling receiver ResolveInfo{2e9b22ed com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5119): enabling receiver ResolveInfo{d004522 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5119): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 5983): TimaSignature is unavailable
D/PackageManager( 1021): delete codoeFile: 
D/ActivityThread( 5983): Added TimaKeyStore provider
D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10338 Target=com.test.thalitest
D/PackageManager( 1021): result of delete: 1{663068300}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 5950): Shutting down VM
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
D/UserAnalysis.PlaceProvider( 5983): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 5983): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5983): SecurePlaceDbHelper() 
D/UserAnalysis( 5983): Create SecureDbHelper
D/IntelligenceServiceApplication( 5983): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5983): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 4457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 5983): no applications having user consent for prediction
E/Zygote  ( 5999): MountEmulatedStorage()
E/Zygote  ( 5999): v2
I/libpersona( 5999): KNOX_SDCARD checking this for 1000
I/libpersona( 5999): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::stopService] Service stopped.
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/SELinux ( 5999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 4706:com.google.android.gms:car/u0a11 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/TimaKeyStoreProvider( 5999): TimaSignature is unavailable
D/ActivityThread( 5999): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
W/ResourcesManager( 5999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 5983): 276926830: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 5983): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5983): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/RCPManager( 5999):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5161): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5161): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5161): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5161): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5161): before removeFromFS
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/art     ( 5950): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6016 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6016): MountEmulatedStorage()
I/libpersona( 6016): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6016): v2
I/libpersona( 6016): KNOX_SDCARD not a persona
I/SELinux ( 6016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 6025): MountEmulatedStorage()
I/libpersona( 6025): KNOX_SDCARD checking this for 10095
E/Zygote  ( 6025): v2
I/libpersona( 6025): KNOX_SDCARD not a persona
I/SELinux ( 6025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6025 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 6025): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1021): failed to open /acct/uid_10011/pid_4706/cgroup.procs: No such file or directory
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
D/TimaKeyStoreProvider( 6016): TimaSignature is unavailable
D/ActivityThread( 6016): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6025): TimaSignature is unavailable
D/ActivityThread( 6025): Added TimaKeyStore provider
W/ContextImpl( 6016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6049): MountEmulatedStorage()
I/libpersona( 6049): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD not a persona
D/PreloadFilterInstaller( 6025): uses FILTER_DB_VER_1
I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/SQLiteLog( 6025): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SQLiteDatabase( 6025): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6025): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6025): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6025): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6025): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6025): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6025): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6025): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6025): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6025): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteOpenHelper( 6025): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6025): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6025): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6025): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6025): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6025): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6025): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6025): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6025): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6025): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6025): Opened filter.db in read-only mode
E/SQLiteLog( 6025): (284) automatic index on titles(filter_id)
E/SQLiteLog( 6016): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6016): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6016): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6016): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6016): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6016): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6016): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6016): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6016): Process: com.android.keychain, PID: 6016
E/AndroidRuntime( 6016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6016): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6016): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6016): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6016): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.keychain
D/ActivityThread( 6049): Added TimaKeyStore provider
E/SQLiteLog( 6025): (284) automatic index on titles(filter_id)
I/Process ( 6016): Sending signal. PID: 6016 SIG: 9
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1021): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1021): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1021): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1021): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1021): 	... 5 more
I/ActivityManager( 1021): Killing 3918:com.sec.spp.push/u0a32 (adj 15): empty #31

```
