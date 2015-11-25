#### Test 503880196dc97cd_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
I/ServiceManager(  355): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6238): 
D/AndroidRuntime( 6238): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6238): CheckJNI is OFF
D/AndroidRuntime( 6238): readGMSProperty: start
D/AndroidRuntime( 6238): readGMSProperty: already setted!!
D/AndroidRuntime( 6238): readGMSProperty: end
D/AndroidRuntime( 6238): addProductProperty: start
E/AffinityControl( 6238): AffinityControl: registerfunction enter
D/AndroidRuntime( 6238): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  753): inState():  stateMachine is null !!
I/PersonaManagerService(  753): PersonaId don't exist
I/ActivityManager(  753): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  753): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  753): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  753): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  753): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  753): Set to : 0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6254): MountEmulatedStorage()
E/Zygote  ( 6254): v2
I/libpersona( 6254): KNOX_SDCARD checking this for 10255
I/libpersona( 6254): KNOX_SDCARD not a persona
I/SELinux ( 6254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6254): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager(  753): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6254 uid=10255 gids={50255, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PointerIcon(  753): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  753): setMouseCustomIcon IconType is same.101
D/PointerIcon(  753): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  753): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6238): Shutting down VM
D/TimaKeyStoreProvider( 6254): TimaSignature is unavailable
D/ActivityThread( 6254): Added TimaKeyStore provider
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  753): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  753): Display changed displayId=0
D/SurfaceWidgetView( 1426): destroyHardwareResources():1013859571
D/ConnectivityService(  753): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6254): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/PowerManagerService(  753): [PWL] Off : 30s ago
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1765): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1426): updateVisibility : ActivityRecord{299bb518 token=android.os.BinderProxy@2015186d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1426): onTrimMemory. Level: 20
I/WebViewFactory( 6254): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6254): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/SSRM:n  (  753): SIOP:: AP = 340, PST = 397, CUR = 450
I/LibraryLoader( 6254): Loading: webviewchromium
I/LibraryLoader( 6254): Time to load native libraries: 5 ms (timestamps 9419-9424)
I/LibraryLoader( 6254): Expected native library version number "",actual native library version number ""
I/ServiceManager(  355): Waiting for service AtCmdFwd...
V/WebViewChromiumFactoryProvider( 6254): Binding Chromium to main looper Looper (main, tid 1) {270c6a75}
I/LibraryLoader( 6254): Expected native library version number "",actual native library version number ""
I/chromium( 6254): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6254): Initializing chromium process, renderers=0
W/art     ( 6254): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6254): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6254): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6254): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6254): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 6254): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6254): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6254): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6254): Local Branch: mybranch5813579
I/Adreno-EGL( 6254): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6254): Local Patches: NONE
I/Adreno-EGL( 6254): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
D/BluetoothAdapter( 6254): 876030474: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6254): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6254): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ActivityManager(  753): Activity pause timeout for ActivityRecord{5e5eb71 u0 com.example.hello/.MainActivity t2}
W/art     ( 6254): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6254): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6254): CordovaWebView is running on device made by: samsung
W/art     ( 6254): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6254): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6254): performCreate Call secproduct feature valuefalse
D/Activity( 6254): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6254): Render dirty regions requested: true
D/Atlas   ( 6254): Validating map...
D/ActivityManager(  753): post active user change for 0
D/KnoxTimeoutHandler(  753): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  753): handleActiveUserChange for user 0
V/ActivityThread( 6254): updateVisibility : ActivityRecord{2562a06b token=android.os.BinderProxy@54ddae5 {com.example.hello/com.example.hello.MainActivity}} show : true
I/SurfaceFlinger(  254): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  753): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  753): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  753): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  753): setMouseCustomIcon IconType is same.101
D/PointerIcon(  753): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  753): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6254): Initialized EGL, version 1.4
I/OpenGLRenderer( 6254): HWUI protection enabled for context ,  &this =0xb3c15b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6254): Enabling debug mode 0
,D/InputMethodManagerService(  753): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  753): mDVFSHelper.release()
I/Timeline(  753): Timeline: Activity_windows_visible id: ActivityRecord{5e5eb71 u0 com.example.hello/.MainActivity t2} time:80091
W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1716): getCurrentCandidateView
W/IInputConnectionWrapper( 6254): showStatusIcon on inactive InputConnection
I/Timeline( 6254): Timeline: Activity_idle id: android.os.BinderProxy@54ddae5 time:80107
E/SMD     (  299): DCD ON
D/SamsungIME( 1716): Dismiss ExpandCandiate
E/AndroidProtocolHandler( 6254): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 6254): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/chromium( 6254): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6254): 
I/SamsungIME( 1716): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6254): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1716): getDebugLevel  : 0x4f4c
I/SamsungIME( 1716): KeybaordView init() : load resources
I/SamsungIME( 1716): getCurrentKeyboard
I/SamsungIME( 1716): getTextKeyboard
I/ServiceManager(  355): Waiting for service AtCmdFwd...
D/SamsungIME( 1716): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6254): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258384384
D/JX-Cordova( 6254): jxcore cordova android initializing
W/jxcore-log( 6254): Initializing JXcore engine
W/jxcore-log( 6254): JXcore engine is ready
W/jxcore-log( 6254): Starting JXcore engine
,E/auditd  ( 1818): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  753): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  753): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6342): MountEmulatedStorage()
I/libpersona( 6342): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6342): v2
I/libpersona( 6342): KNOX_SDCARD not a persona
,I/ActivityManager(  753): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6254): Platform android
W/jxcore-log( 6254): 
W/jxcore-log( 6254): Process ARCH arm
W/jxcore-log( 6254): 
,I/SELinux ( 6342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 6254): JXcore Cordova bridge is ready!
I/jxcore-log( 6254): 
,W/jxcore-log( 6254): JXcore engine is started
,D/TimaKeyStoreProvider( 6342): TimaSignature is unavailable
D/ActivityThread( 6342): Added TimaKeyStore provider
,D/SamsungIME( 1716): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ResourcesManager( 6342): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6342):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6342):  SeDenialReceiver : File path = null
,I/ActivityManager(  753): Killing 5253:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/jxcore-log( 6254): >> samsung-SM-N9005
E/jxcore-log( 6254): 
,I/jxcore-log( 6254): Total memory 2971471872
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): Free memory 455131136
I/jxcore-log( 6254): 
I/jxcore-log( 6254): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6254): 
I/jxcore-log( 6254): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): Size 1080 1920
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): Screen Brightness 162
I/jxcore-log( 6254): 
,E/jxcore-log( 6254): Dummy Error Log.
E/jxcore-log( 6254): 
,I/ServiceManager(  355): Waiting for service AtCmdFwd...
,I/jxcore-log( 6254): getBuffer is called!!!!
I/jxcore-log( 6254): 
,I/ServiceManager(  355): Waiting for service AtCmdFwd...
,V/AlarmManager(  753): waitForAlarm result :4
,E/SMD     (  299): DCD ON
,D/BatteryService(  753): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  753): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  753): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  753): Sending ACTION_BATTERY_CHANGED.
D/LightsService(  753): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 753) 
D/LightsService(  753): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
E/LightSensor(  753): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/MotionRecognitionService(  753): Plugged
,I/MotionRecognitionService(  753): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  753): uri = 14 selection = getSealedState
,D/SecContentProvider2(  753): mCursor = null
,D/SensorManager(  753): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  753): turn on LED for fully charged
,D/ApplicationPolicy(  753): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  753): isApplicationStateBlocked userId -2 pkgname com.android.systemui
D/WindowManager(  753): showStatusBarByNotification() mOpenByNotification=false
I/AudioService(  753): getStreamVolume 1 index 0
D/NotificationService(  753): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  753): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
V/Vibrator(  753): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
,V/Vibrator(  753): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
D/VibratorService(  753): Turning vibrator off - ImmVibe.
,D/PowerManagerService(  753): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1183
,I/PowerManagerService(  753): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  753): Waking up from sleep (uid 10067)...
,D/PowerManagerService(  753): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate(  753): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@a22e58a)
,D/KeyguardViewMediator( 1183): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1183): notifyScreenOnLocked
,D/PowerManagerService(  753): [s] UserActivityState : 0 -> 1
,D/PowerManagerService(  753): [PWL] sb acquire: PowerManagerService.Display
I/DisplayPowerController(  753): Blocking screen on until initial contents have been drawn.
,D/SContextService(  753): 	.registerCallback : 1, client=
,W/CAE     (  753): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/AutomaticBrightnessController(  753): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  753): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  753): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
,D/AutomaticBrightnessController(  753): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerManagerService(  753): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,I/CAE     (  753): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  753): setCAProperty(ContextAwareService.java:469) - result : true
,D/MISC PowerHAL(  753): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  753): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
W/CAE     (  753): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  753): sendAttribute() : service = Auto Rotation
,W/CAE     (  753): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  753): start(ContextProvider.java:126)
,I/QCOM PowerHAL(  753): Got set_interactive hint
V/CAE     (  753): clear(AutoRotationRunner.java:182)
,V/CAE     (  753): enable(AutoRotationRunner.java:158)
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/CAE     (  753): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  753): SendSensorHubData: send data = -79, 7, 0, 0
D/AutomaticBrightnessController(  753): [api] [DAB] onSensorChanged : 1st lux : 10.7614
D/AutomaticBrightnessController(  753): [DAB] updateAutoBrightnessSEC : 29(29.0)    0.0 < 10.7614 < 24.0 (0.0)
D/AutomaticBrightnessController(  753): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  753): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
,D/SensorManager(  753): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/PowerManagerService(  753): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 8ms
D/Sensorhubs(  323): sendContextData: -79, 7, 0, 0
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/AutomaticBrightnessController(  753): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/Sensors (  753): Acc old sensor_state 512, new sensor_state : 513 en : 1
I/AutomaticBrightnessController(  753): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController(  753): getFinalBrightness : 29 -> 29
,D/DisplayPowerController(  753): animation target = 29, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
,I/DisplayManagerService(  753): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  753): Display changed displayId=0
,D/CAE     (  753): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,D/SensorManager(  753): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  753): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 16ms
,I/CAE     (  753): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/DisplayPowerController(  753): getFinalBrightness : 29 -> 29
D/DisplayPowerController(  753): animation target = 29, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KnoxNotification( 1183): ----- inflateViews : modified publicViewLocal -----
,D/CAE     (  753): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  753): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  753): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     (  753): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2cefcb24, Service : AUTO_ROTATION(1)
W/CAE     (  753): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  753): addSContextService() : service = Auto Rotation
D/SContextService(  753): ===== SContext Service List =====
D/SContextService(  753): Listener : android.hardware.scontext.SContextService$Listener@33d6a68d, Service : Auto Rotation
D/SContextManager(  753):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@587f7fb, service=Auto Rotation
,D/KnoxNotification( 1183): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1183): PersonaID is invalid or persona doesn't exists. : 0
,D/InputManager-JNI(  753): setDeviceInteractive: 1
,D/InputManager-JNI(  753): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/SamsungIME( 1716): showDlgMsgBox : false true true
D/InputManager-JNI(  753): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  753): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/NativeNfcManager( 1412): power state=4
,D/InputManager-JNI(  753): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/NfcService( 1412): call the applyRotuiing
,D/PalmMotion(  753): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/PalmMotion(  753): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  753):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  753): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 753) 
D/LightsService(  753): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SSRM:a  (  753): DeviceInfo:: 000000100000
D/SSRM:a  (  753): SettingsAirViewInfo:: 010100000
D/KeyguardViewMediator( 1183): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1183): onScreenTurnedOn()
,D/LightsService(  753): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 753) 
D/LightsService(  753): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  753): turn off LED
,D/LightsService(  753): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SensorManager(  753): unregisterListener ::   
D/lights  (  753): led_pattern : 0 +
D/lights  (  753): led_pattern : 0 -
,D/LightsService(  753): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/UserPresentBroadcastReceiver( 1480): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/StatusBar.NetworkController( 1183): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
,D/ActivityManager(  753): post active user change for 0
D/KnoxTimeoutHandler(  753): postActiveUserChange for user 0
,D/StatusBar.NetworkController( 1183): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
I/CAE     (  753): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,V/KeyguardServiceDelegate(  753): **** SHOWN CALLED ****
D/DisplayPowerController(  753): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/StatusBarKeyguardViewManager( 1183): callback.onShown()
I/DisplayPowerController(  753): Unblocked screen on after 159 ms
D/DisplayPowerState(  753): !@ ColorFade exit
,I/CAE     (  753): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  753): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  753): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  323): sendContextData: -76, 13, -47, 0
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (8/8)
,E/libEGL  (  753): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  753): getFinalBrightness : 29 -> 29
D/DisplayPowerController(  753): animation target = 29, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  753): lcd : 29 +
D/lights  (  753): lcd : 29 -
I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/8)
,D/DisplayPowerController(  753): getFinalBrightness : 29 -> 29
D/DisplayPowerController(  753): animation target = 29, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  753): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  753): SecHardwareInterface.setBatteryADC : true
,D/KnoxTimeoutHandler(  753): handleActiveUserChange for user 0
D/PowerManagerService(  753): [input device light] setInputDeviceLightOn is called : 1
D/lights  (  753): button : 1 +
D/PowerManagerService(  753): [input device light] handleInputDeviceLightOn
,D/InputMethodManagerService(  753): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  753):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiNative-HAL(  753): startHal
E/wifi    (  753): getStaticLongField sWifiHalHandle 0x9b9d180c
D/wifi    (  753): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501ea2
I/WifiNative-HAL(  753): Could not start hal
,W/Atfwd_Sendcmd(  355): AtCmdFwd service not published, waiting... retryCnt : 5
,E/MotionRecognitionService(  753):  handler : SCREEN_ON end
D/NotificationService(  753): ACTION_SCREEN_ON
D/LightsService(  753): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 753) 
D/LightsService(  753): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  753): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  753): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/InputManager-JNI(  753): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,D/audio_hw_primary(  310): adev_set_parameters: enter: screen_state=on
,V/voice   (  310): voice_set_parameters: enter: screen_state=on
V/voice   (  310): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  310): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  310): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  310): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  310): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  753): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  753): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  753): Bridge Server is not available
,D/lights  (  753): button : 1 -
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
,D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
,D/SurfaceControl(  753): Excessive delay in setPowerMode(): 251ms
D/PowerManagerService(  753): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 263ms
,I/SurfaceFlinger(  254): id=12 createSurf (1080x750),1 flag=4, Ieads Up
,D/BatteryMeterView( 1183): onDraw batteryColor : -1
,D/GpsLocationProvider(  753): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  753): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  753): MSG_ACTION_SCREEN_ON called
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
,I/NfcService( 1412): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1412): call the applyRotuiing
,W/ResourcesManager(  753): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,D/accuweather( 1765): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,D/accuweather( 1765): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,I/Timeline( 6254): Timeline: Activity_idle id: android.os.BinderProxy@54ddae5 time:83654
,I/SamsungIME( 1716): getNextShiftState() cursorCapsMode : 0
,D/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25130428k
,D/ConnectivityService(  753): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3340): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1448460708447
,D/SSRM:n  (  753): SIOP:: AP = 340, PST = 390, CUR = 450
,D/InputManager-JNI(  753): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/PowerManagerService(  753): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3340): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 3340): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3340): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3340): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 11/25/2015 04:18 PM
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 11/25/2015 03:11 PM
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3340): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/Finsky  ( 5465): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5465): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 1567): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:a  (  753): DeviceInfo:: 000000100000
D/SSRM:a  (  753): SettingsAirViewInfo:: 010100000
,D/PowerManagerService(  753): [input device light] handleInputDeviceLightOff
,D/lights  (  753): button : 0 +
,D/lights  (  753): button : 0 -
,W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  299): DCD ON
,D/BluetoothAdapter( 6254): disable()
E/BluetoothManagerService(  753): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6254): packageName : com.example.hello
,D/SecContentProvider(  753): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  753): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  753): mCursor = null
,D/WifiService(  753): setWifiEnabled: false pid=6254, uid=10255
,D/SettingsProvider(  753): name = wifi_on
,I/jxcore-log( 6254): ****TEST TOOK:  5080  ms ****
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6254): 
,D/AndroidRuntime( 6423): 
D/AndroidRuntime( 6423): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6423): CheckJNI is OFF
,D/AndroidRuntime( 6423): readGMSProperty: start
,D/AndroidRuntime( 6423): readGMSProperty: already setted!!
,D/AndroidRuntime( 6423): readGMSProperty: end
,D/AndroidRuntime( 6423): addProductProperty: start
,E/AffinityControl( 6423): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6423): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  753): START PACKAGE DELETE: observer{997082452}
D/PackageManager(  753): pkg{<packageName>}
D/PackageManager(  753): user{0}
D/PackageManager(  753): caller{2000}
D/PackageManager(  753): flags{3}
,D/PersonaManagerService(  753): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  753): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  753): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  753): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  753): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  753): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  753): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  753): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  753): getApplicationUninstallationEnabled
D/ApplicationPolicy(  753): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  753): !@killApplicatoin: 10255, uninstall pkg
,I/ActivityManager(  753): Force stopping com.example.hello appid=10255 user=-1: uninstall pkg
I/ActivityManager(  753): Killing 6254:com.example.hello/u0a255 (adj 0): stop com.example.hello
,W/PackageSettings(  753): Skipping PackageSetting{1e053291 com.test.thalitest/10254} due to missing metadata
,I/WindowState(  753): WIN DEATH: Window{2a22afbf u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,D/PointerIcon(  753): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  753): setMouseCustomIcon IconType is same.101
D/PointerIcon(  753): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  753): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  753): Force removing ActivityRecord{5e5eb71 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  753): Set to : 0
,D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  753): mDVFSHelper.acquire()
,V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  753): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  753): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/ActivityManager(  753): Display changed displayId=0
,W/ActivityManager(  753): Spurious death for ProcessRecord{1a0b4cfd 6254:com.example.hello/u0a255}, curProc for 6254: null
,D/ConnectivityService(  753): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SurfaceWidgetView( 1426): destroyHardwareResources():1013859571
,I/ActivityManager(  753): Force stopping com.example.hello appid=10255 user=0: pkg removed
,D/Launcher( 1426): onRestart, Launcher: 874896598
,D/Launcher( 1426): onStart, Launcher: 874896598
D/Launcher.HomeView( 1426): onStart
,D/Launcher( 1426): onResume, Launcher: 874896598
,D/SettingsProvider(  753): name = kids_home_mode
D/SettingsProvider(  753): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  753): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  753): selectionArgs: false
D/SettingsProvider(  753): selectionArgs: 10010
D/SecContentProvider(  753): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  753): ret = -1
D/Launcher.HomeView( 1426): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1765): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1765): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1765): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/Launcher( 1426): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/accuweather( 1765): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1765): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
D/Launcher( 1426): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1765): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1716): mOCRHelper is null
I/InputReader(  753): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/accuweather( 1765): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
D/accuweather( 1765): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
,D/accuweather( 1765): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1765): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
D/accuweather( 1765): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1765): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1765): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,I/art     ( 4843): Explicit concurrent mark sweep GC freed 37551(2012KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 15MB/26MB, paused 456us total 43.759ms
E/Zygote  ( 6452): MountEmulatedStorage()
I/libpersona( 6452): KNOX_SDCARD checking this for 10023
E/Zygote  ( 6452): v2
I/libpersona( 6452): KNOX_SDCARD not a persona
,I/ActivityManager(  753): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6452 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/accuweather( 1765): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 6013): Explicit concurrent mark sweep GC freed 5316(262KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 366us total 86.384ms
,I/art     ( 6078): Explicit concurrent mark sweep GC freed 9828(552KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 386us total 62.687ms
,I/art     (  753): Explicit concurrent mark sweep GC freed 39476(2MB) AllocSpace objects, 19(304KB) LOS objects, 17% free, 37MB/45MB, paused 1.184ms total 109.661ms
I/art     (  753): WaitForGcToComplete blocked for 35.119ms for cause Explicit
,D/ResourcesManager(  753): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/SELinux ( 6452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/comsamsunglog( 1765): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1765): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1765): [Accuweather J]>>> Header set to : ===> "accuweather" <===
,D/comsamsunglog( 1765): [Accuweather J]>>> ==============================================================================================
,I/SELinux ( 6452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/MenuAppsGridFragment( 1426): onResume
,E/SELinux ( 6452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WallpaperManager( 1426): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1426): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1765): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,D/accuweather( 1765): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1765): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/EnterpriseDeviceManagerService(  753): Package has changed for user 0
D/EnterpriseDeviceManagerService(  753): Admin package name: com.google.android.gms
,D/ActivityManager(  753): handle home activity for 0
I/WallpaperManagerService(  753): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  753): post home show event for user 0
,D/accuweather( 1765): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/ActivityManager(  753): post active user change for 0
D/KnoxTimeoutHandler(  753): postActiveUserChange for user 0
D/accuweather( 1765): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
D/TimaKeyStoreProvider( 6452): TimaSignature is unavailable
,D/ActivityThread( 6452): Added TimaKeyStore provider
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/accuweather( 1765): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Wed, 25 November
,D/SurfaceWidget.Renderer( 1765): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1765): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/SecContentProvider2(  753): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  753): mCursor = null
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  753): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/PointerIcon(  753): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  753): setMouseCustomIcon IconType is same.101
D/PointerIcon(  753): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  753): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 6452): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/Launcher( 1426): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1426): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/InputMethodManagerService(  753): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  753): Got RemoteException sending setActive(false) notification to pid 6254 uid 10255
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/MicrophoneInputStream( 1624): mic_starting gfk@3ade862e
,I/HotwordRecognitionRnr( 1624): Starting hotword detection.
,V/AudioPolicyManager(  310): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  310): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  310): adev_open_input_stream: enter
E/audio_hw_primary(  310): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  310): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  310): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  310): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  310): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  310): adev_open_input_stream: exit
,I/AudioFlinger(  310): AudioFlinger's thread 0xb1733000 ready to run
V/audio_hw_primary(  310): in_standby: enter
,V/audio_hw_primary(  310): in_standby: exit:  status(0)
,V/audio_hw_primary(  310): in_standby: enter
,V/audio_hw_primary(  310): in_standby: exit:  status(0)
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/EDMNativeHelperService(  753): isMicrophoneEnabled
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.511: ( 6452): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/AudioPolicyManager(  310): startInput() input 14
V/AudioPolicyManager(  310): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  310): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  310): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  310): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,V/audio_hw_primary(  310): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
,V/audio_hw_primary(  310): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  310): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  310): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1624): mic_started gfk@3ade862e
,D/StatusBarManagerService(  753): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/WallpaperManager( 1426): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/RegisteredServicesCache( 1412): empty dynamic service
,D/WallpaperManager( 1426): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,V/msm8974_platform(  310): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  310): start_input_stream: enter: usecase(7)
V/voice   (  310): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  310): start_input_stream: usecase(7)
,D/PreProcess(  310): new SamsungRecord
D/PreProcess(  310): new NS
I/samsungRecord(  310): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  310): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  310): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  310): 1
D/SamsungRecord_NS(  310): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  310): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
,V/audio_hw_primary(  310): select_devices: ENTER
V/audio_hw_primary(  310): select_devices: usecase(normal)
V/audio_hw_primary(  310): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  310): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  310): get_INPUT_snd_device: check by Input_source(6)
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
V/msm8974_platform(  310): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  310): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
,V/msm8974_platform(  310): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  310): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  310): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  310): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  310): ACDB -> send_adm_topology
D/ACDB-LOADER(  310): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  310): ACDB -> send_asm_topology
,D/ACDB-LOADER(  310): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  310): ACDB -> send_audtable
D/ACDB-LOADER(  310): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  310): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  310): ACDB -> send_audvoltable
D/ACDB-LOADER(  310): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  310): Failed to fetch the lookup information of the device 00000035 
,E/ACDB-LOADER(  310): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  310): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  310): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  310): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  310): ++++ audio_route_update_mixer ==============
D/audio_route(  310): Setting mixer control: ADC1 Volume
,D/audio_route(  310): Setting mixer control: value: 19
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/audio_route(  310): Setting mixer control: DEC6 Volume
,D/audio_route(  310): Setting mixer control: value: 84
D/audio_route(  310): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  310): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  310): Setting mixer control: value: 1
,I/KLMS-2.4.511: ( 6452): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448460712013
,D/audio_route(  310): Setting mixer control: DEC6 MUX, value: 2
,I/KLMS-2.4.511: ( 6452): MainReciver(): PACKAGE_REMOVED
,D/audio_route(  310): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  310): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  310): enable_audio_route: apply mixer path: audio-record
D/audio_route(  310): ++++ audio_route_update_mixer ==============
D/audio_route(  310): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  310): Setting mixer control: value: 1
,D/audio_route(  310): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  310): enable_audio_route: exit
V/audio_hw_primary(  310): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  310): start_input_stream: exit
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.511: ( 6452): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/Timeline( 1426): Timeline: Activity_idle id: android.os.BinderProxy@2015186d time:87291
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/HotwordWorker( 1624): onReady
,I/art     (  753): Explicit concurrent mark sweep GC freed 9473(573KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.539ms total 250.512ms
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  753): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/RCPManagerService(  753): PackageReceiver onReceive()
,I/HarmonyEASService(  753): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/PackageManager(  753): delete codoeFile: 
,D/KnoxMUMContainerPolicy(  753): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  753): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  753): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  753): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,E/Zygote  ( 6477): MountEmulatedStorage()
V/EnterpriseBillingPolicy(  753): uID is 10255
V/EnterpriseBillingPolicy(  753): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  753): getProfileForApplication - enter
E/Zygote  ( 6477): v2
I/libpersona( 6477): KNOX_SDCARD checking this for 10116
I/libpersona( 6477): KNOX_SDCARD not a persona
,V/EnterpriseBillingPolicyStorage(  753): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  753): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  753): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  753): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  753): getBillingProfileForVpnEngine - end - null
,I/AASAUninstall(  753):  com.example.hello not target!
,D/PackageManager(  753): result of delete: 1{997082452}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,I/ActivityManager(  753): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6477 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,D/WallpaperManagerService(  753):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  753): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  753): handleActiveUserChange for user 0
,I/ActivityManager(  753): Killing 5053:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/5053/oom_score_adj; errno=22
,D/TaskPersister(  753): removeObsoleteFile: deleting file=2_task.xml
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,I/SELinux ( 6477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SELinux ( 6477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/AndroidRuntime( 6423): Shutting down VM
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TimaKeyStoreProvider( 6477): TimaSignature is unavailable
,D/ActivityThread( 6477): Added TimaKeyStore provider
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/CustomFrequencyManagerService(  753): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 753  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  753): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager( 6477): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  753): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  753): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  753): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14491( 6477): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491( 6477): ELMEngine.ELMEngine( context ).
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/elm:14491( 6477): MDMBridge.setEnterpriseBridge()
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/elm:14491( 6477): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  753): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14491( 6477): ElmAgentService : onCreate()
,E/Zygote  ( 6493): MountEmulatedStorage()
E/Zygote  ( 6493): v2
I/libpersona( 6493): KNOX_SDCARD checking this for 10021
I/libpersona( 6493): KNOX_SDCARD not a persona
,D/elm:14491( 6477): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6477): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6477): MDMBridge.getInstance()
D/elm:14491( 6477): MDMBridge.getAllLicenseInfoFromSDK()
,I/ActivityManager(  753): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6493 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/Timeline(  753): Timeline: Activity_windows_visible id: ActivityRecord{3c91b1dc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:87552
,D/UsbSettingsManager(  753): clearDefaults: com.example.hello
I/CrashAnrDetector(  753): onPackageRemoved : com.example.hello
,I/SELinux ( 6493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6493): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491( 6477): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6477): ElmAgentService : onDestroy().
,I/ActivityManager(  753): Killing 4409:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6493): TimaSignature is unavailable
,D/ActivityThread( 6493): Added TimaKeyStore provider
,D/ResourcesManager( 6493): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6493): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 6493): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6493): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5767): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5767): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5767): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5767): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6511): MountEmulatedStorage()
I/libpersona( 6511): KNOX_SDCARD checking this for 10043
E/Zygote  ( 6511): v2
I/libpersona( 6511): KNOX_SDCARD not a persona
,I/ActivityManager(  753): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6511 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  753): Killing 5092:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/SELinux ( 6511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6511): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  753): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 753  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 6511): TimaSignature is unavailable
,D/ActivityThread( 6511): Added TimaKeyStore provider
,D/ResourcesManager( 6511): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6511): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6511): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6511): PushLog.txt file is not deleted.
,D/SPPClientService( 6511): PushLog.txt file is not deleted.
D/SPPClientService( 6511): ============PushLog. stop!
,I/EventHub(  753): Removing device '/dev/input/event6' due to inotify event
,E/SQLiteLog( 6511): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6511): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6511): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6511): (14) os_unix.c:32503: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,E/SQLiteDatabase( 6511): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6511): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6511): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6511): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6511): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6511): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/LNoti   ( 6511): [b] open fail. SQLException occured
,I/SA      ( 5864): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5864): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10255 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  753): Killing 5349:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/SharedPreferencesImpl( 4883): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,D/Mms/FreeMessageReceiver( 4781): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  753): enable value -1
,I/TactileAssist(  753): internal enable value -1
I/TactileAssist(  753): intensity value -1
I/TactileAssist(  753): saveAppList value true
I/TactileAssist(  753): List of disabled apps :
E/SharedPreferencesImpl(  753): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
D/Mms/FreeMessageReceiverService( 4781): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4781): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/EventHub(  753): Removing device '/dev/input/event7' due to inotify event
,D/SettingsProvider(  753): name = reading_mode_app_list
,D/Compatibility( 5896): onReceive() it will make start service
,D/Compatibility( 5896): onHandleIntent()
,D/Compatibility( 5896): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10255, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5896): found: 2
D/Compatibility( 5896): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5896): skipping ResolveInfo{1bc638f1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5896): considering ResolveInfo{3425dcd6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5896): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5896): enabling receiver ResolveInfo{20ec6b57 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/UpdateIcingCorporaServi( 1624): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/EventHub(  753): Removing device '/dev/input/event8' due to inotify event
,W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 5896): enabling receiver ResolveInfo{29a86644 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/RCPManager( 5370):  in createShortcut() for packageName: com.example.hello userId0
D/Compatibility( 5896): enabling receiver ResolveInfo{2874732d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/RCPManagerService(  753):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  753): queryAllProviders():  providerCallBack is not register for 0
,D/Compatibility( 5896): enabling receiver ResolveInfo{367af062 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SQLiteLog( 5072): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5072): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5072): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5072): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5072): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5072): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5072): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5072): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5072): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5072): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5072): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5072): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 5072): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5072): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5072): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,W/System.err( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5072): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5072): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5072): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 5072): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub(  753): Removing device '/dev/input/event9' due to inotify event
,E/SharedPreferencesImpl( 5896): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,W/ContextImpl( 6013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,E/SQLiteLog( 1624): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1624): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1624): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04d24e1 in tid 6531 (IntentService[U)
,E/SharedPreferencesImpl( 5896): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5896): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6534): MountEmulatedStorage()
,E/Zygote  ( 6534): v2
I/libpersona( 6534): KNOX_SDCARD checking this for 10121
I/libpersona( 6534): KNOX_SDCARD not a persona
,I/ActivityManager(  753): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6534 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/EventHub(  753): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 6534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6534): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  753): checkUser: useridlist=null, currentuser=0
,I/DEBUG   (  295): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  295): failed to open /data/tombstones: No such file or directory
E/        (  295): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1624
,I/EventHub(  753): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  ( 6545): MountEmulatedStorage()
,D/TimaKeyStoreProvider( 6534): TimaSignature is unavailable
E/Zygote  ( 6545): v2
I/libpersona( 6545): KNOX_SDCARD checking this for 1000
I/libpersona( 6545): KNOX_SDCARD not a persona
I/dumpstate( 6542): begin
,I/dumpstate( 6542): open lockfile failed No such file or directory
E/dumpstate( 6542): Cannot get free space size. So, skip dumpstate.
,D/ActivityThread( 6534): Added TimaKeyStore provider
,I/ActivityManager(  753): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6545 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub(  753): Removing device '/dev/input/event12' due to inotify event
,I/SELinux ( 6545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/audit_log( 1818): File locking failed. error= Bad file number
,D/ResourcesManager( 6534): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,W/ContextImpl( 6534): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6534): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  753): Removing device '/dev/input/event13' due to inotify event
,E/SQLiteLog( 6534): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6534): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6534): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6534): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
,E/SQLiteDatabase( 6534): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6534): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6534): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6534): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6534): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6534): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6534): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6534): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper( 6534): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6534): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6534): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 6534): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6534): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper( 6534): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteOpenHelper( 6534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteOpenHelper( 6534): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 6534): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteLog( 6534): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6534): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6534): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
,E/SQLiteDatabase( 6534): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6534): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/SQLiteDatabase( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6534): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6534): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6534): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6534): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 6534): Writing exception to parcel
E/DatabaseUtils( 6534): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/DatabaseUtils( 6534): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/DatabaseUtils( 6534): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/DatabaseUtils( 6534): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/DatabaseUtils( 6534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6534): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6534): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AndroidRuntime( 6013): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 6013): Process: com.samsung.android.app.filterinstaller, PID: 6013
E/AndroidRuntime( 6013): android.database.sqlite.SQLiteException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6013): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
E/AndroidRuntime( 6013): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 6013): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
E/AndroidRuntime( 6013): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/AndroidRuntime( 6013): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime( 6013): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromFS(FilterUninstaller.java:101)
E/AndroidRuntime( 6013): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:42)
E/AndroidRuntime( 6013): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 6013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6013): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ApplicationPolicy(  753): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.filterinstaller
D/ResourcesManager(  753): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/TimaKeyStoreProvider( 6545): TimaSignature is unavailable
D/ActivityThread( 6545): Added TimaKeyStore provider
E/AndroidRuntime(  753): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  753): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  753): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  753): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  753): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  753): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  753): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  753): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  753): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  753): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  753): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  753): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  753): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  753): 	... 5 more
D/StatusBarManagerService(  753): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  753): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  753): setMouseCustomIcon IconType is same.101
D/PointerIcon(  753): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  753): setHoveringSpenCustomIcon IconType is same.1
,F/libc    (  753): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa97a6028 in tid 902 (ActivityManager)
,I/EventHub(  753): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager( 6545): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,W/ContextImpl( 6545): Unable to create files subdir /data/data/com.android.keychain/cache
,E/ActivityThread( 6545): Unable to setupGraphicsSupport due to missing cache directory
,W/ContextImpl( 6545): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2991 
,E/SQLiteLog( 6545): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6545): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6545): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6545): (14) os_unix.c:32503: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
,E/SQLiteDatabase( 6545): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6545): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6545): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase( 6545): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase( 6545): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6545): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6545): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6545): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 6545): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6545): Process: com.android.keychain, PID: 6545
E/AndroidRuntime( 6545): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6545): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime( 6545): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime( 6545): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6545): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6545): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6545): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/AudioPolicyManager(  310): stopInput() input 14
V/AudioPolicyManager(  310): releaseInput() 14
V/AudioPolicyManager(  310): closeInput(14)
,V/audio_hw_primary(  310): in_standby: enter
,I/ActivityManager(  753): Process com.google.android.googlequicksearchbox:search (pid 1624)(adj 1) has died(516,1356)
,I/Zygote  (  343): Process 1624 exited due to signal (7)
W/ActivityManager(  753): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  753): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,W/ActivityManager(  753): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
,I/ActivityManager(  753): Killing 5428:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,V/audio_hw_primary(  310): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  310): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  310): disable_audio_route: reset mixer path: audio-record
D/audio_route(  310): ++++ audio_route_update_mixer ==============
D/audio_route(  310): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  310): Setting mixer control: value: 0
,D/audio_route(  310): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  310): disable_audio_route: exit
V/audio_hw_primary(  310): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  310): ++++ audio_route_update_mixer ==============
D/audio_route(  310): Setting mixer control: ADC1 Volume
D/audio_route(  310): Setting mixer control: value: 0
D/audio_route(  310): Setting mixer control: DEC6 Volume
D/audio_route(  310): Setting mixer control: value: 0
,D/audio_route(  310): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  310): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  310): Setting mixer control: value: 0
D/audio_route(  310): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  310): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  310): stop_input_stream: exit: status(0)
V/audio_hw_primary(  310): in_standby: exit:  status(0)
,V/audio_hw_primary(  310): adev_close_input_stream
V/audio_hw_primary(  310): in_standby: enter
V/audio_hw_primary(  310): in_standby: exit:  status(0)
E/audio_hw_primary(  310): adev_close_input_stream, set jack_in to null
,V/AudioPolicyManager(  310): releaseInput() exit
,V/ApplicationPolicy(  753): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,I/Process (  753): Sending signal. PID: 753 SIG: 9
,E/audit_log( 1818): File locking failed. error= Bad file number
,E/DEBUG   (  295): unexpected waitpid response: n=902, status=00000009
E/        (  295): ptrace detach from 902 failed: No such process
E/        (  295): debuggerd committing suicide to free the zombie!
,W/AudioFlinger(  310): power manager service died !!!
W/AudioCache(  310): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
,W/Sensors ( 4883): sensorservice died [0xaf1df240]
I/ServiceManager(  252): service 'lock_settings' died
W/Sensors ( 1765): sensorservice died [0xaf19e640]
I/ServiceManager(  252): service 'device_policy' died
W/Sensors ( 1921): sensorservice died [0xaf1d8a40]
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'clipboard' died
E/WifiManager( 1567): Channel connection lost
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
W/Sensors ( 1480): sensorservice died [0xaf1a4340]
I/ServiceManager(  252): service 'netstats' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'connectivity' died
I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
I/ServiceManager(  252): service 'notification' died
W/Sensors ( 1419): sensorservice died [0xaf19a240]
I/ServiceManager(  252): service 'devicestoragemonitor' died
I/ServiceManager(  252): service 'location' died
I/ServiceManager(  252): service 'country_detector' died
I/ServiceManager(  252): service 'search' died
I/ServiceManager(  252): service 'dropbox' died
I/ServiceManager(  252): service 'wallpaper' died
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'backup' died
I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
I/ServiceManager(  252): service 'samplingprofiler' died
I/ServiceManager(  252): service 'commontime_management' died
I/ServiceManager(  252): service 'dreams' died
I/ServiceManager(  252): service 'assetatlas' died
I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
I/ServiceManager(  252): service 'media_router' died
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'activity' died
W/Sensors ( 1397): sensorservice died [0xaf1d99c0]
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
E/WifiManager( 1480): Channel connection lost
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
W/Sensors ( 1426): sensorservice died [0xaf19a300]
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' die,d
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'edmnativehelper' died
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6962000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/SurfaceFlinger(  254): id=13 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (4/7)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/7)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (-2/7)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (5/6)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (5/5)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/5)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (2/4)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (2/3)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (-2/3)
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (2/2)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/1)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/0)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/0)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/0)
E/WifiManager( 1419): Channel connection lost
E/WifiManager( 1309): Channel connection lost
W/Sensors ( 1183): sensorservice died [0xaf19c1c0]
E/WifiManager( 1183): Channel connection lost
E/AndroidRuntime( 6545): Error reporting crash
E/AndroidRuntime( 6545): android.os.DeadObjectException
E/AndroidRuntime( 6545): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6545): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6545): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6545): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6545): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6545): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6545): Sending signal. PID: 6545 SIG: 9
E/AndroidRuntime( 6013): Error reporting crash
E/AndroidRuntime( 6013): android.os.DeadObjectException
E/AndroidRuntime( 6013): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6013): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6013): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6013): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6013): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6013): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6013): Sending signal. PID: 6013 SIG: 9
E/installd(  319): eof
E/installd(  319): failed to read size
I/installd(  319): closing connection
E/EsApplication( 5443): Uncaught exception in background thread Thread[IntentService[GPlusPackageMediaMonitor],5,main]
E/EsApplication( 5443): android.os.DeadObjectException
E/EsApplication( 5443): 	at android.os.BinderProxy.transactNative(Native Method)
E/EsApplication( 5443): 	at android.os.BinderProxy.transact(Binder.java:496)
E/EsApplication( 5443): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/EsApplication( 5443): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/EsApplication( 5443): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/EsApplication( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/EsApplication( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/EsApplication( 5443): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/EsApplication( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/EsApplication( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/EsApplication( 5443): 	at android.os.Looper.loop(Looper.java:145)
E/EsApplication( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5443): FATAL EXCEPTION: IntentService[GPlusPackageMediaMonitor]
E/AndroidRuntime( 5443): Process: com.google.android.apps.plus, PID: 5443
E/AndroidRuntime( 5443): android.os.DeadObjectException
E/AndroidRuntime( 5443): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5443): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5443): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/AndroidRuntime( 5443): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/AndroidRuntime( 5443): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/AndroidRuntime( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/AndroidRuntime( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/AndroidRuntime( 5443): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/AndroidRuntime( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5443): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/EsApplication( 5443): Uncaught exception in background thread Thread[IntentService[GPlusPackageMediaMonitor],5,main]
E/EsApplication( 5443): java.lang.RuntimeException: Package manager has died
E/EsApplication( 5443): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:687)
E/EsApplication( 5443): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/EsApplication( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/EsApplication( 5443): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/EsApplication( 5443): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/EsApplication( 5443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/EsApplication( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/EsApplication( 5443): 	at android.os.Looper.loop(Looper.java:145)
E/EsApplication( 5443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/EsApplication( 5443): Caused by: android.os.DeadObjectException
E/EsApplication( 5443): 	at android.os.BinderProxy.transactNative(Native Method)
E/EsApplication( 5443): 	at android.os.BinderProxy.transact(Binder.java:496)
E/EsApplication( 5443): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/EsApplication( 5443): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/EsApplication( 5443): 	... 8 more
E/AndroidRuntime( 5443): Error reporting crash
E/AndroidRuntime( 5443): android.os.DeadObjectException
E/AndroidRuntime( 5443): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5443): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5443): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5443): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5443): 	at ewf.run(PG:348)
E/AndroidRuntime( 5443): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5443): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5443): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 5443): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5443): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5443): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 5443): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
I/Process ( 5443): Sending signal. PID: 5443 SIG: 9
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
,I/SurfaceFlinger(  254): Disp[0] Orientation 0=>0

```
