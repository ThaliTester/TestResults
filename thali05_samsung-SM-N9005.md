#### Test 502422852e23b2c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  296): DCD ON
,--------- beginning of system
E/Watchdog(  742): !@Sync 2
D/AndroidRuntime( 6003): 
D/AndroidRuntime( 6003): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6003): CheckJNI is OFF
D/AndroidRuntime( 6003): readGMSProperty: start
D/AndroidRuntime( 6003): readGMSProperty: already setted!!
D/AndroidRuntime( 6003): readGMSProperty: end
D/AndroidRuntime( 6003): addProductProperty: start
W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl( 6003): AffinityControl: registerfunction enter
D/AndroidRuntime( 6003): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  742): inState():  stateMachine is null !!
I/PersonaManagerService(  742): PersonaId don't exist
I/ActivityManager(  742): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  742): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  742): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  742): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  742): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  742): Set to : 0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  742): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6018 uid=10265 gids={50265, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PointerIcon(  742): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  742): setMouseCustomIcon IconType is same.101
D/PointerIcon(  742): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  742): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6003): Shutting down VM
E/Zygote  ( 6018): MountEmulatedStorage()
I/libpersona( 6018): KNOX_SDCARD checking this for 10265
E/Zygote  ( 6018): v2
I/libpersona( 6018): KNOX_SDCARD not a persona
I/SELinux ( 6018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6018): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6018): TimaSignature is unavailable
D/ActivityThread( 6018): Added TimaKeyStore provider
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  742): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  742): Display changed displayId=0
D/SurfaceWidgetView( 1449): destroyHardwareResources():615888550
D/ConnectivityService(  742): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6018): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
V/ActivityThread( 1449): updateVisibility : ActivityRecord{2b4a526f token=android.os.BinderProxy@17b6b3e6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1449): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1767): [237392/8] Surface widget visibility changed visibility = false on instance = 1
,I/WebViewFactory( 6018): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6018): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6018): Loading: webviewchromium
,I/LibraryLoader( 6018): Time to load native libraries: 6 ms (timestamps 6611-6617)
,I/LibraryLoader( 6018): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6018): Binding Chromium to main looper Looper (main, tid 1) {29ad3993}
,I/LibraryLoader( 6018): Expected native library version number "",actual native library version number ""
,I/chromium( 6018): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6018): Initializing chromium process, renderers=0
,W/art     ( 6018): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6018): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6018): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6018): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6018): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6018): 553549264: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6018): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6018): Local Branch: mybranch5813579
I/Adreno-EGL( 6018): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6018): Local Patches: NONE
I/Adreno-EGL( 6018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6018): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6018): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6018): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6018): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6018): CordovaWebView is running on device made by: samsung
,W/art     ( 6018): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6018): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  742): Activity pause timeout for ActivityRecord{35d2556 u0 com.example.hello/.MainActivity t2}
,D/Activity( 6018): performCreate Call secproduct feature valuefalse
,D/Activity( 6018): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6018): Render dirty regions requested: true
,D/Atlas   ( 6018): Validating map...
,D/ActivityManager(  742): post active user change for 0
,D/KnoxTimeoutHandler(  742): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  742): handleActiveUserChange for user 0
,V/ActivityThread( 6018): updateVisibility : ActivityRecord{18290f39 token=android.os.BinderProxy@14e7ad83 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  742): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  742): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/OpenGLRenderer( 6018): Initialized EGL, version 1.4
,D/PointerIcon(  742): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  742): setMouseCustomIcon IconType is same.101
D/PointerIcon(  742): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  742): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6018): HWUI protection enabled for context ,  &this =0xa1a53060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6018): Enabling debug mode 0
,D/InputMethodManagerService(  742): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1714): getCurrentCandidateView
,W/ActivityManager(  742): mDVFSHelper.release()
I/Timeline(  742): Timeline: Activity_windows_visible id: ActivityRecord{35d2556 u0 com.example.hello/.MainActivity t2} time:77093
,W/IInputConnectionWrapper( 6018): showStatusIcon on inactive InputConnection
,I/Timeline( 6018): Timeline: Activity_idle id: android.os.BinderProxy@14e7ad83 time:77100
,I/chromium( 6018): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6018): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/SamsungIME( 1714): Dismiss ExpandCandiate
,D/JsMessageQueue( 6018): Set native->JS mode to OnlineEventsBridgeMode
,E/SMD     (  296): DCD ON
,I/chromium( 6018): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6018): 
,I/SamsungIME( 1714): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1714): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1714): KeybaordView init() : load resources
,D/jxcore_app_log( 6018): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358062464
,D/JX-Cordova( 6018): jxcore cordova android initializing
,I/SamsungIME( 1714): getCurrentKeyboard
I/SamsungIME( 1714): getTextKeyboard
,D/SamsungIME( 1714): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 6018): Initializing JXcore engine
W/jxcore-log( 6018): JXcore engine is ready
,W/jxcore-log( 6018): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  742): Got Modify Event and sending Denial Intent foraudit.log
E/auditd  ( 1863): In denial and Property audit_ondenial is set to 1 
W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  742): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6097): MountEmulatedStorage()
E/Zygote  ( 6097): v2
I/libpersona( 6097): KNOX_SDCARD checking this for 1000
I/libpersona( 6097): KNOX_SDCARD not a persona
,I/ActivityManager(  742): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6097 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6097): TimaSignature is unavailable
,D/ActivityThread( 6097): Added TimaKeyStore provider
,W/jxcore-log( 6018): Platform android
W/jxcore-log( 6018): 
,W/jxcore-log( 6018): Process ARCH arm
W/jxcore-log( 6018): 
,D/ResourcesManager( 6097): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/jxcore-log( 6018): JXcore Cordova bridge is ready!
I/jxcore-log( 6018): 
,W/jxcore-log( 6018): JXcore engine is started
,D/SecurityLogAgent( 6097):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6097):  SeDenialReceiver : File path = null
,I/ActivityManager(  742): Killing 5164:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,E/jxcore-log( 6018): >> samsung-SM-N9005
E/jxcore-log( 6018): 
,I/jxcore-log( 6018): Total memory 2971471872
I/jxcore-log( 6018): 
,I/jxcore-log( 6018): Free memory 450752512
I/jxcore-log( 6018): 
I/jxcore-log( 6018): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6018): 
I/jxcore-log( 6018): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6018): 
,I/jxcore-log( 6018): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6018): 
,I/jxcore-log( 6018): Size 1080 1920
I/jxcore-log( 6018): 
,I/jxcore-log( 6018): Screen Brightness 162
I/jxcore-log( 6018): 
,E/jxcore-log( 6018): Dummy Error Log.
E/jxcore-log( 6018): 
,D/SamsungIME( 1714): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 6018): getBuffer is called!!!!
I/jxcore-log( 6018): 
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/PowerManagerService(  742): [PWL] Off : 30s ago
,D/SSRM:n  (  742): SIOP:: AP = 330, PST = 381, CUR = 450
,V/AlarmManager(  742): waitForAlarm result :4
,D/BatteryService(  742): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  742): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  742): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/LightsService(  742): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 742) 
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/LightSensor(  742): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  742): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  742): turn on LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/BatteryService(  742): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  742): uri = 14 selection = getSealedState
,D/SecContentProvider2(  742): mCursor = null
,D/NtpTrustedTime(  742): forceRefresh() from cache miss
,I/MotionRecognitionService(  742): Plugged
I/MotionRecognitionService(  742): setPowerConnected  = true
,D/NtpTrustedTime(  742): forceRefresh Fail.
,D/ApplicationPolicy(  742): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  742): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  742): showStatusBarByNotification() mOpenByNotification=false
,I/AudioService(  742): getStreamVolume 1 index 0
V/Vibrator(  742): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
D/NotificationService(  742): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  742): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
D/VibratorService(  742): Turning vibrator off - ImmVibe.
V/Vibrator(  742): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
,D/PowerManagerService(  742): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1192
I/PowerManagerService(  742): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
,I/PowerManagerService(  742): Waking up from sleep (uid 10067)...
D/PowerManagerService(  742): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  742): [s] UserActivityState : 0 -> 1
V/KeyguardServiceDelegate(  742): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2a0b6ebf)
,D/KeyguardViewMediator( 1192): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1192): notifyScreenOnLocked
,I/DisplayPowerController(  742): Blocking screen on until initial contents have been drawn.
,D/PowerManagerService(  742): [PWL] sb acquire: PowerManagerService.Display
,D/AutomaticBrightnessController(  742): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  742): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  742): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DisplayPowerController(  742): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
,D/SContextService(  742): 	.registerCallback : 1, client=
W/CAE     (  742): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,I/CAE     (  742): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  742): setCAProperty(ContextAwareService.java:469) - result : true
D/AutomaticBrightnessController(  742): [api] [DAB] onSensorChanged : 1st lux : 9.9482
D/AutomaticBrightnessController(  742): [DAB] updateAutoBrightnessSEC : 26(26.0)    0.0 < 9.9482 < 22.0 (0.0)
D/AutomaticBrightnessController(  742): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  742): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  742): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,I/AutomaticBrightnessController(  742): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 9
D/DisplayPowerController(  742): getFinalBrightness : 26 -> 26
D/DisplayPowerController(  742): animation target = 26, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/MISC PowerHAL(  742): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService(  742): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  742): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
W/CAE     (  742): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
I/QCOM PowerHAL(  742): Got set_interactive hint
,D/SContextService(  742): sendAttribute() : service = Auto Rotation
,W/CAE     (  742): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  742): start(ContextProvider.java:126)
,V/CAE     (  742): clear(AutoRotationRunner.java:182)
I/DisplayManagerService(  742): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  742): Display changed displayId=0
V/CAE     (  742): enable(AutoRotationRunner.java:158)
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/CAE     (  742): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
,D/SensorHubManager(  742): SendSensorHubData: send data = -79, 7, 0, 0
,D/SensorManager(  742): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/PowerManagerService(  742): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 15ms
E/Sensors (  742): Acc old sensor_state 512, new sensor_state : 513 en : 1
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/Sensorhubs(  309): sendContextData: -79, 7, 0, 0
,D/SensorManager(  742): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  742): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 9ms
,I/art     ( 1744): Explicit concurrent mark sweep GC freed 32871(2MB) AllocSpace objects, 15(240KB) LOS objects, 25% free, 21MB/28MB, paused 519us total 62.842ms
,D/CAE     (  742): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  742): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/SMD     (  296): DCD ON
,D/DisplayPowerController(  742): getFinalBrightness : 26 -> 26
D/DisplayPowerController(  742): animation target = 26, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KnoxNotification( 1192): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1192): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1192): PersonaID is invalid or persona doesn't exists. : 0
,D/CAE     (  742): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  742): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  742): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     (  742): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@23bec4a7, Service : AUTO_ROTATION(1)
,W/CAE     (  742): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  742): addSContextService() : service = Auto Rotation
,D/SContextService(  742): ===== SContext Service List =====
D/SContextService(  742): Listener : android.hardware.scontext.SContextService$Listener@184ecd54, Service : Auto Rotation
D/SContextManager(  742):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@956898c, service=Auto Rotation
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/PalmMotion(  742): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
,D/InputManager-JNI(  742): setDeviceInteractive: 1
E/MotionRecognitionService(  742):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion(  742): SURFACE_PALM_SWIPE: 1
D/LightsService(  742): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 742) 
D/NativeNfcManager( 1414): power state=4
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/InputManager-JNI(  742): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/SamsungIME( 1714): showDlgMsgBox : false true true
,D/NfcService( 1414): call the applyRotuiing
,D/InputManager-JNI(  742): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/SSRM:a  (  742): DeviceInfo:: 000000100000
D/SSRM:a  (  742): SettingsAirViewInfo:: 010100000
,D/InputManager-JNI(  742): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  742): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/KeyguardViewMediator( 1192): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1192): onScreenTurnedOn()
,D/StatusBar.NetworkController( 1192): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/LightsService(  742): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 742) 
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=false enabledDesc:null
,D/LightsService(  742): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SensorManager(  742): unregisterListener ::   
D/lights  (  742): led_pattern : 0 +
,D/lights  (  742): led_pattern : 0 -
D/LightsService(  742): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  742): turn off LED
,V/UserPresentBroadcastReceiver( 1480): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager(  742): post active user change for 0
D/KnoxTimeoutHandler(  742): postActiveUserChange for user 0
,D/StatusBar.NetworkController( 1192): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=false enabledDesc:null
D/KnoxTimeoutHandler(  742): handleActiveUserChange for user 0
,I/CAE     (  742): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  742): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  742): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  742): SendSensorHubData: send data = -76, 13, -47, 0
D/StatusBarKeyguardViewManager( 1192): callback.onShown()
,V/KeyguardServiceDelegate(  742): **** SHOWN CALLED ****
,D/DisplayPowerController(  742): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  742): Unblocked screen on after 166 ms
D/DisplayPowerState(  742): !@ ColorFade exit
,D/Sensorhubs(  309): sendContextData: -76, 13, -47, 0
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (8/8)
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/8)
,E/libEGL  (  742): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  742): getFinalBrightness : 26 -> 26
D/DisplayPowerController(  742): animation target = 26, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  742): lcd : 26 +
D/lights  (  742): lcd : 26 -
D/DisplayPowerController(  742): getFinalBrightness : 26 -> 26
D/DisplayPowerController(  742): animation target = 26, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  742): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  742): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  742): [input device light] setInputDeviceLightOn is called : 1
D/lights  (  742): button : 1 +
D/PowerManagerService(  742): [input device light] handleInputDeviceLightOn
,D/InputMethodManagerService(  742): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  742):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/EventLogService( 1744): Aggregate from 1449495473580 (log), 1449495473580 (data)
,E/MotionRecognitionService(  742):  handler : SCREEN_ON end
,I/WifiNative-HAL(  742): startHal
E/wifi    (  742): getStaticLongField sWifiHalHandle 0x9bff780c
D/wifi    (  742): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601c22
I/WifiNative-HAL(  742): Could not start hal
D/NotificationService(  742): ACTION_SCREEN_ON
D/LightsService(  742): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 742) 
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  742): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  742): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  303): adev_set_parameters: enter: screen_state=on
V/voice   (  303): voice_set_parameters: enter: screen_state=on
V/voice   (  303): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  303): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  303): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  303): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  303): adev_set_parameters: exit
D/InputManager-JNI(  742): sysfs_write -: /sys/class/input/event4/device/enabled: 1
I/SecExternalDisplayIntents_Java(  742): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/IpRemoteDisplayController(  742): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  742): Bridge Server is not available
,D/lights  (  742): button : 1 -
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
D/SurfaceControl(  742): Excessive delay in setPowerMode(): 259ms
I/SurfaceFlinger(  254): id=12 createSurf (1080x750),1 flag=4, Ieads Up
D/PowerManagerService(  742): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 263ms
,D/BatteryMeterView( 1192): onDraw batteryColor : -1
,I/Timeline( 6018): Timeline: Activity_idle id: android.os.BinderProxy@14e7ad83 time:80443
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
D/GpsLocationProvider(  742): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  742): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  742): MSG_ACTION_SCREEN_ON called
,W/ResourcesManager(  742): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,I/NfcService( 1414): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1414): call the applyRotuiing
,D/accuweather( 1767): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,D/accuweather( 1767): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SamsungIME( 1714): getNextShiftState() cursorCapsMode : 0
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25134040k
,D/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
I/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,D/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3295): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1449497288284
,D/ConnectivityService(  742): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InputManager-JNI(  742): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/PowerManagerService(  742): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  (  742): SIOP:: AP = 330, PST = 375, CUR = 450
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 3295): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3295): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
,D/comsamsunglog( 3295): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3295): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/Finsky  ( 5422): [895] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5422): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 12/07/2015 09:07 PM
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 12/07/2015 03:08 PM
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3295): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/SQLiteLog( 1563): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/SSRM:a  (  742): DeviceInfo:: 000000100000,
,D/SSRM:a  (  742): SettingsAirViewInfo:: 010100000,
,D/PowerManagerService(  742): [input device light] handleInputDeviceLightOff
,D/lights  (  742): button : 0 +
,D/lights  (  742): button : 0 -
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BluetoothAdapter( 6018): disable()
,E/BluetoothManagerService(  742): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6018): packageName : com.example.hello
,D/SecContentProvider(  742): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  742): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  742): mCursor = null
,D/WifiService(  742): setWifiEnabled: false pid=6018, uid=10265
,D/SettingsProvider(  742): name = wifi_on
,I/jxcore-log( 6018): ****TEST TOOK:  5065  ms ****
I/jxcore-log( 6018): 
,I/jxcore-log( 6018): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6018): 
,D/AndroidRuntime( 6186): 
D/AndroidRuntime( 6186): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6186): CheckJNI is OFF
,D/AndroidRuntime( 6186): readGMSProperty: start
D/AndroidRuntime( 6186): readGMSProperty: already setted!!
,D/AndroidRuntime( 6186): readGMSProperty: end
,D/AndroidRuntime( 6186): addProductProperty: start
,E/AffinityControl( 6186): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6186): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  742): START PACKAGE DELETE: observer{116432802}
D/PackageManager(  742): pkg{<packageName>}
D/PackageManager(  742): user{0}
D/PackageManager(  742): caller{2000}
D/PackageManager(  742): flags{3}
D/PersonaManagerService(  742): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  742): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  742): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  742): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  742): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  742): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  742): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  742): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  742): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  742): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  742): !@killApplicatoin: 10265, uninstall pkg
,I/ActivityManager(  742): Force stopping com.example.hello appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  742): Killing 6018:com.example.hello/u0a265 (adj 0): stop com.example.hello
,E/SMD     (  296): DCD ON
,W/PackageSettings(  742): Skipping PackageSetting{35238b08 com.test.thalitest/10266} due to missing metadata
,I/WindowState(  742): WIN DEATH: Window{510be8c u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,D/PointerIcon(  742): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  742): setMouseCustomIcon IconType is same.101
D/PointerIcon(  742): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  742): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  742): Force removing ActivityRecord{35d2556 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  742): Set to : 0
,D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  742): mDVFSHelper.acquire()
,V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  742): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  742): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/ActivityManager(  742): Display changed displayId=0
,D/SurfaceWidgetView( 1449): destroyHardwareResources():615888550
,W/ActivityManager(  742): Spurious death for ProcessRecord{1e638433 6018:com.example.hello/u0a265}, curProc for 6018: null
,I/ActivityManager(  742): Force stopping com.example.hello appid=10265 user=0: pkg removed
,D/Launcher( 1449): onRestart, Launcher: 226562437
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 5
,I/art     ( 5824): Explicit concurrent mark sweep GC freed 2155(127KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 419us total 21.090ms
I/art     ( 4246): Explicit concurrent mark sweep GC freed 7139(441KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 429us total 25.507ms
,D/Launcher( 1449): onStart, Launcher: 226562437
D/Launcher.HomeView( 1449): onStart
,D/Launcher( 1449): onResume, Launcher: 226562437
D/SettingsProvider(  742): name = kids_home_mode
D/SettingsProvider(  742): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  742): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  742): selectionArgs: false
D/SettingsProvider(  742): selectionArgs: 10010
D/SecContentProvider(  742): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  742): ret = -1
,D/Launcher.HomeView( 1449): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1767): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1767): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
,D/accuweather( 1767): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
,D/accuweather( 1767): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1767): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/Launcher( 1449): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/Launcher( 1449): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/ConnectivityService(  742): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1767): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,E/SamsungIME( 1714): mOCRHelper is null
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 4048): Explicit concurrent mark sweep GC freed 38528(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 444us total 39.253ms
,D/accuweather( 1767): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
D/accuweather( 1767): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1767): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
,D/accuweather( 1767): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1767): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1767): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
D/accuweather( 1767): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,I/InputReader(  742): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  ( 6215): MountEmulatedStorage()
I/libpersona( 6215): KNOX_SDCARD checking this for 10023
E/Zygote  ( 6215): v2
I/libpersona( 6215): KNOX_SDCARD not a persona
,I/ActivityManager(  742): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6215 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/accuweather( 1767): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,I/SELinux ( 6215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/EnterpriseDeviceManagerService(  742): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  742): Admin package name: com.google.android.gms
,I/SELinux ( 6215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/comsamsunglog( 1767): [Accuweather J]>>> ==============================================================================================
,D/comsamsunglog( 1767): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
,D/comsamsunglog( 1767): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1767): [Accuweather J]>>> ==============================================================================================
D/MenuAppsGridFragment( 1449): onResume
,D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1767): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/accuweather( 1767): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1767): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ActivityManager(  742): handle home activity for 0
D/accuweather( 1767): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
I/WallpaperManagerService(  742): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  742): post home show event for user 0
D/ActivityManager(  742): post active user change for 0
D/accuweather( 1767): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
D/KnoxTimeoutHandler(  742): postActiveUserChange for user 0
,D/accuweather( 1767): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Mon, 7 December
,D/accuweather( 1767): [Accuweather J]>>> SM:2087 [0:0] makeTimeText[1] time :Mon, 7 December 15:07 , new :Mon, 7 December 15:08 
,D/accuweather( 1767): [Accuweather J]>>> SM:2208 [0:0] uCCV : msg = -1, oT = true
,I/art     (  742): Explicit concurrent mark sweep GC freed 44290(3MB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 37MB/45MB, paused 1.654ms total 154.357ms
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  742): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  742): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     (  742): WaitForGcToComplete blocked for 149.133ms for cause Explicit
,D/accuweather( 1767): [Accuweather J]>>> SM:2171 [0:0] uCCV : time = 15:08
,D/PointerIcon(  742): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  742): setMouseCustomIcon IconType is same.101
D/PointerIcon(  742): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  742): setHoveringSpenCustomIcon IconType is same.1
,D/TimaKeyStoreProvider( 6215): TimaSignature is unavailable
,D/ActivityThread( 6215): Added TimaKeyStore provider
,D/Launcher( 1449): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1449): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  742): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SurfaceWidget.Renderer( 1767): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1767): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager( 6215): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/InputMethodManagerService(  742): Got RemoteException sending setActive(false) notification to pid 6018 uid 10265
,W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  742): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  742): mCursor = null
,I/MicrophoneInputStream( 1621): mic_starting gfk@2213a9e5
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,V/AudioPolicyManager(  303): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  303): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  303): adev_open_input_stream: enter
E/audio_hw_primary(  303): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  303): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  303): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  303): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  303): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  303): adev_open_input_stream: exit
,I/AudioFlinger(  303): AudioFlinger's thread 0xb1733000 ready to run
V/audio_hw_primary(  303): in_standby: enter
V/audio_hw_primary(  303): in_standby: exit:  status(0)
,I/HotwordRecognitionRnr( 1621): Starting hotword detection.
,V/audio_hw_primary(  303): in_standby: enter
V/audio_hw_primary(  303): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  742): isMicrophoneEnabled
,I/KLMS-2.4.511: ( 6215): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/AudioPolicyManager(  303): startInput() input 14
,V/AudioPolicyManager(  303): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  303): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  303): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  303): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
V/audio_hw_primary(  303): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  303): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  303): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  303): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1621): mic_started gfk@2213a9e5
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.511: ( 6215): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449497291368
,I/KLMS-2.4.511: ( 6215): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.511: ( 6215): MainReciver(): REPLACING: false | pkgName: com.example.hello
,V/msm8974_platform(  303): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  303): start_input_stream: enter: usecase(7)
V/voice   (  303): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  303): start_input_stream: usecase(7)
D/PreProcess(  303): new SamsungRecord
D/PreProcess(  303): new NS
I/samsungRecord(  303): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  303): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  303): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  303): 1
D/SamsungRecord_NS(  303): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  303): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  303): select_devices: ENTER
V/audio_hw_primary(  303): select_devices: usecase(normal)
V/audio_hw_primary(  303): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  303): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  303): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  303): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  303): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  303): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  303): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  303): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  303): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  303): ACDB -> send_adm_topology
D/ACDB-LOADER(  303): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  303): ACDB -> send_asm_topology
D/ACDB-LOADER(  303): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  303): ACDB -> send_audtable
D/ACDB-LOADER(  303): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  303): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  303): ACDB -> send_audvoltable
D/ACDB-LOADER(  303): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  303): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  303): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  303): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  303): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  303): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: ADC1 Volume
D/audio_route(  303): Setting mixer control: value: 19
,D/audio_route(  303): Setting mixer control: DEC6 Volume
D/audio_route(  303): Setting mixer control: value: 84
,D/audio_route(  303): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  303): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  303): Setting mixer control: value: 1
,D/audio_route(  303): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  303): enable_audio_route: apply mixer path: audio-record
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  303): Setting mixer control: value: 1
,D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): enable_audio_route: exit
V/audio_hw_primary(  303): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  303): start_input_stream: exit
,D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1449): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/StatusBarManagerService(  742): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 1414): empty dynamic service
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/Timeline( 1449): Timeline: Activity_idle id: android.os.BinderProxy@17b6b3e6 time:83732
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/HotwordWorker( 1621): onReady
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,E/Zygote  ( 6238): MountEmulatedStorage()
E/Zygote  ( 6238): v2
I/libpersona( 6238): KNOX_SDCARD checking this for 10116
I/libpersona( 6238): KNOX_SDCARD not a persona
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ActivityManager(  742): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6238 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  742): Killing 5199:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/5199/oom_score_adj; errno=22
,I/art     (  742): Explicit concurrent mark sweep GC freed 8054(459KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 36MB/44MB, paused 1.563ms total 254.847ms
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,I/SELinux ( 6238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  742): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 742  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  742): mDVFSHelper.release()
D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/RCPManagerService(  742): PackageReceiver onReceive()
I/HarmonyEASService(  742): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  742): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/PackageManager(  742): delete codoeFile: 
D/BackupManagerService(  742): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  742): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  742): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  742): uID is 10265
V/EnterpriseBillingPolicy(  742): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  742): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  742): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  742): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  742): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  742): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  742): getBillingProfileForVpnEngine - end - null
,I/AASAUninstall(  742):  com.example.hello not target!
,D/PackageManager(  742): result of delete: 1{116432802}
,D/AndroidRuntime( 6186): Shutting down VM
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/TimaKeyStoreProvider( 6238): TimaSignature is unavailable
,D/ActivityThread( 6238): Added TimaKeyStore provider
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/WallpaperManagerService(  742):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler(  742): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  742): handleActiveUserChange for user 0
,D/TaskPersister(  742): removeObsoleteFile: deleting file=2_task.xml
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 6238): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/elm:14491( 6238): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491( 6238): ELMEngine.ELMEngine( context ).
,D/elm:14491( 6238): MDMBridge.setEnterpriseBridge()
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/elm:14491( 6238): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/elm:14491( 6238): ElmAgentService : onCreate()
,D/elm:14491( 6238): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6238): MainReceiver.listeningToPackageRemoved()
,D/elm:14491( 6238): MDMBridge.getInstance()
,D/elm:14491( 6238): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/elm:14491( 6238): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,E/Zygote  ( 6254): MountEmulatedStorage()
I/libpersona( 6254): KNOX_SDCARD checking this for 10021
E/Zygote  ( 6254): v2
I/libpersona( 6254): KNOX_SDCARD not a persona
,W/ResourcesManager(  742): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  742): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  742): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/ActivityManager(  742): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6254 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/Timeline(  742): Timeline: Activity_windows_visible id: ActivityRecord{21329432 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:83992
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,I/SELinux ( 6254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 6238): ElmAgentService : onDestroy().
I/art     (  340): Explicit concurrent mark sweep GC freed 8757(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 317us total 13.115ms
,I/SELinux ( 6254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6254): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/ActivityManager(  742): Killing 5006:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 10.452ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 281us total 10.110ms
,D/TimaKeyStoreProvider( 6254): TimaSignature is unavailable
,D/ActivityThread( 6254): Added TimaKeyStore provider
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 6254): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  742): clearDefaults: com.example.hello
,I/CrashAnrDetector(  742): onPackageRemoved : com.example.hello
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6254): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 6254): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6254): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5682): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5682): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5682): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,D/CustomFrequencyManagerService(  742): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 742  tag : ACTIVITY_RESUME_BOOSTER@11
,E/Zygote  ( 6273): MountEmulatedStorage()
,E/Zygote  ( 6273): v2
I/libpersona( 6273): KNOX_SDCARD checking this for 10043
I/libpersona( 6273): KNOX_SDCARD not a persona
,I/ActivityManager(  742): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6273 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  742): Killing 4349:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 6273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6273): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6273): TimaSignature is unavailable
D/ActivityThread( 6273): Added TimaKeyStore provider
,D/ResourcesManager( 6273): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6273): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6273): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6273): PushLog.txt file is not deleted.
,I/EventHub(  742): Removing device '/dev/input/event6' due to inotify event
D/SPPClientService( 6273): PushLog.txt file is not deleted.
D/SPPClientService( 6273): ============PushLog. stop!
,E/SQLiteLog( 6273): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6273): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6273): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6273): (14) os_unix.c:32503: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,E/SQLiteDatabase( 6273): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6273): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6273): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6273): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6273): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6273): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6273): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6273): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6273): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6273): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/LNoti   ( 6273): [b] open fail. SQLException occured
I/SA      ( 5764): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 5764): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10265 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  742): Killing 5042:com.google.android.talk/u0a131 (adj 13): bgCount ##41
E/SharedPreferencesImpl( 4799): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
D/Mms/FreeMessageReceiver( 4867): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  742): enable value -1
,I/TactileAssist(  742): internal enable value -1
I/TactileAssist(  742): intensity value -1
I/TactileAssist(  742): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4867): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4867): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist(  742): List of disabled apps :
,E/SharedPreferencesImpl(  742): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,D/SettingsProvider(  742): name = reading_mode_app_list
,D/Compatibility( 5785): onReceive() it will make start service
,D/Compatibility( 5785): onHandleIntent()
,D/Compatibility( 5785): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10265, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/EventHub(  742): Removing device '/dev/input/event7' due to inotify event
,I/UpdateIcingCorporaServi( 1621): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5785): found: 2
,D/Compatibility( 5785): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5785): skipping ResolveInfo{1a95a6fc com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5785): considering ResolveInfo{d811185 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5785): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5785): enabling receiver ResolveInfo{25292bda com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ContextImpl( 5026): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 5785): enabling receiver ResolveInfo{2280480b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5785): enabling receiver ResolveInfo{a1436e8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5785): enabling receiver ResolveInfo{12c64101 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SharedPreferencesImpl( 5785): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5785): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5785): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/EventHub(  742): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog( 1621): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 1621): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1621): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa041e4e1 in tid 6293 (IntentService[U)
,D/RCPManager( 5327):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  742):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  742): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5026): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 5026): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5026): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5026): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5026): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5026): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5026): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5026): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5026): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5026): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5026): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5026): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5026): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 5026): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5026): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,W/System.err( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5026): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 5026): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5026): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5026): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5026): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5026): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,W/System.err( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5026): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5026): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
,W/System.err( 5026): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5026): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5026): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ContextImpl( 5824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,I/EventHub(  742): Removing device '/dev/input/event9' due to inotify event
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,I/DEBUG   (  292): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  292): failed to open /data/tombstones: No such file or directory
E/        (  292): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1621
,I/EventHub(  742): Removing device '/dev/input/event10' due to inotify event
,E/Zygote  ( 6297): MountEmulatedStorage()
E/Zygote  ( 6297): v2
I/libpersona( 6297): KNOX_SDCARD checking this for 10121
I/libpersona( 6297): KNOX_SDCARD not a persona
,I/ActivityManager(  742): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6297 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/dumpstate( 6296): begin
,I/dumpstate( 6296): open lockfile failed No such file or directory
E/dumpstate( 6296): Cannot get free space size. So, skip dumpstate.
,I/SELinux ( 6297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/EventHub(  742): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 6297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6297): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/audit_log( 1863): File locking failed. error= Bad file number
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6297): TimaSignature is unavailable
D/ActivityThread( 6297): Added TimaKeyStore provider
,I/ActivityManager(  742): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6312): MountEmulatedStorage()
E/Zygote  ( 6312): v2
I/libpersona( 6312): KNOX_SDCARD checking this for 1000
I/libpersona( 6312): KNOX_SDCARD not a persona
,I/EventHub(  742): Removing device '/dev/input/event12' due to inotify event
,I/SELinux ( 6312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AudioPolicyManager(  303): stopInput() input 14
V/AudioPolicyManager(  303): releaseInput() 14
V/AudioPolicyManager(  303): closeInput(14)
,V/audio_hw_primary(  303): in_standby: enter
,D/TimaKeyStoreProvider( 6312): TimaSignature is unavailable
,D/ResourcesManager( 6297): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
D/ActivityThread( 6312): Added TimaKeyStore provider
,W/ContextImpl( 6297): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6297): Unable to setupGraphicsSupport due to missing cache directory
,I/Zygote  (  340): Process 1621 exited due to signal (7)
I/ActivityManager(  742): Process com.google.android.googlequicksearchbox:search (pid 1621)(adj 1) has died(511,1361)
,W/ActivityManager(  742): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  742): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
W/ActivityManager(  742): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 21000ms
,I/EventHub(  742): Removing device '/dev/input/event13' due to inotify event
,V/audio_hw_primary(  303): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  303): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  303): disable_audio_route: reset mixer path: audio-record
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  303): Setting mixer control: value: 0
,D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): disable_audio_route: exit
V/audio_hw_primary(  303): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  303): ++++ audio_route_update_mixer ==============
D/audio_route(  303): Setting mixer control: ADC1 Volume
D/audio_route(  303): Setting mixer control: value: 0
D/audio_route(  303): Setting mixer control: DEC6 Volume
D/audio_route(  303): Setting mixer control: value: 0
,D/audio_route(  303): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  303): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  303): Setting mixer control: value: 0
,D/audio_route(  303): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  303): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  303): stop_input_stream: exit: status(0)
V/audio_hw_primary(  303): in_standby: exit:  status(0)
,V/audio_hw_primary(  303): adev_close_input_stream
V/audio_hw_primary(  303): in_standby: enter
V/audio_hw_primary(  303): in_standby: exit:  status(0)
E/audio_hw_primary(  303): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  303): releaseInput() exit
,D/ResourcesManager( 6312): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,E/SQLiteLog( 6297): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 6297): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6297): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6297): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
,E/SQLiteDatabase( 6297): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6297): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6297): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6297): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6297): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6297): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6297): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ContextImpl( 6312): Unable to create files subdir /data/data/com.android.keychain/cache
E/ActivityThread( 6312): Unable to setupGraphicsSupport due to missing cache directory
,E/SQLiteOpenHelper( 6297): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6297): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 6297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6297): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper( 6297): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteOpenHelper( 6297): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteOpenHelper( 6297): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 6297): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteLog( 6297): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6297): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6297): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
,E/SQLiteDatabase( 6297): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6297): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6297): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6297): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6297): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6297): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6297): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 6297): Writing exception to parcel
E/DatabaseUtils( 6297): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/DatabaseUtils( 6297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/DatabaseUtils( 6297): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/DatabaseUtils( 6297): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/DatabaseUtils( 6297): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6297): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6297): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AndroidRuntime( 5824): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5824): Process: com.samsung.android.app.filterinstaller, PID: 5824
E/AndroidRuntime( 5824): android.database.sqlite.SQLiteException: unknown error (code 14): Could not open database
E/AndroidRuntime( 5824): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
E/AndroidRuntime( 5824): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 5824): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
E/AndroidRuntime( 5824): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/AndroidRuntime( 5824): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime( 5824): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromFS(FilterUninstaller.java:101)
E/AndroidRuntime( 5824): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:42)
E/AndroidRuntime( 5824): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5824): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  742): Killing 5303:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,V/ApplicationPolicy(  742): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.filterinstaller
,E/DropBoxManagerService(  742): Can't write: system_app_crash
E/DropBoxManagerService(  742): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: ENOENT (No such file or directory)
E/DropBoxManagerService(  742): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  742): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  742): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  742): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  742): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  742): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/DropBoxManagerService(  742): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/DropBoxManagerService(  742): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  742): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  742): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  742): 	... 5 more
,D/ResourcesManager(  742): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/EventHub(  742): Removing device '/dev/input/event14' due to inotify event
,W/ContextImpl( 6312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2991 
,D/StatusBarManagerService(  742): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  742): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  742): setMouseCustomIcon IconType is same.101
D/PointerIcon(  742): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  742): setHoveringSpenCustomIcon IconType is same.1
,E/SQLiteLog( 6312): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 6312): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131072) and mode_t (0) due to error (2)
,E/SQLiteLog( 6312): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6312): (14) os_unix.c:32503: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
,E/SQLiteDatabase( 6312): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6312): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6312): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6312): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase( 6312): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase( 6312): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6312): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6312): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 6312): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6312): Process: com.android.keychain, PID: 6312
E/AndroidRuntime( 6312): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6312): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6312): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime( 6312): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime( 6312): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6312): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6312): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy(  742): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,F/libc    (  742): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa976f028 in tid 929 (ActivityManager)
,E/DropBoxManagerService(  742): Can't write: system_app_crash
E/DropBoxManagerService(  742): java.io.FileNotFoundException: /data/system/dropbox/drop175.tmp: open failed: ENOENT (No such file or directory)
E/DropBoxManagerService(  742): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  742): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  742): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  742): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  742): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  742): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/DropBoxManagerService(  742): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/DropBoxManagerService(  742): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  742): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  742): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  742): 	... 5 more
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  742): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  742): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6332): MountEmulatedStorage()
E/Zygote  ( 6332): v2
I/libpersona( 6332): KNOX_SDCARD checking this for 1000
I/libpersona( 6332): KNOX_SDCARD not a persona
,I/SELinux ( 6332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DEBUG   (  292): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  292): failed to open /data/tombstones: No such file or directory
E/        (  292): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 742
,I/dumpstate( 6343): begin
I/dumpstate( 6343): open lockfile failed No such file or directory
,E/dumpstate( 6343): Cannot get free space size. So, skip dumpstate.
,E/MotionRecognitionService(  742): Motion Thread--
E/MotionRecognitionService(  742): Motion Thread++
D/MotionRecognitionService(  742): try start thread -1
E/audit_log( 1863): File locking failed. error= Bad file number
,E/installd(  306): eof
E/installd(  306): failed to read size
I/installd(  306): closing connection
,E/AndroidRuntime( 5824): Error reporting crash
E/AndroidRuntime( 5824): android.os.DeadObjectException
E/AndroidRuntime( 5824): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5824): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5824): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5824): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5824): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5824): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 5824): Sending signal. PID: 5824 SIG: 9
W/AudioFlinger(  303): power manager service died !!!
W/AudioCache(  303): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
,I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
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
I/ServiceManager(  252): service 'connectivity' died
I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
I/ServiceManager(  252): service 'notification' died
I/ServiceManager(  252): service 'devicestoragemonitor' died
I/ServiceManager(  252): service 'location' died
I/ServiceManager(  252): service 'country_detector' died
I/ServiceManager(  252): service 'search' died
I/ServiceManager(  252): service 'dropbox' died
I/ServiceManager(  252): service 'wallpaper' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'device_policy' died
,I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
I/ServiceManager(  252): service 'content' died
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
E/WifiManager( 1192): Channel connection lost
W/Sensors ( 1192): sensorservice died [0xaf0dc1c0]
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (5/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (0/2)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (0/1)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (0/0)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (-2/0)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (-2/0)
E/WifiManager( 1312): Channel connection lost
W/Sensors ( 1480): sensorservice died [0xaf0a3340]
E/WifiManager( 1480): Channel connection lost
W/Sensors ( 1925): sensorservice died [0xaf0d8a40]
W/Sensors ( 1423): sensorservice died [0xaf0db240]
E/WifiManager( 1423): Channel connection lost
W/Sensors ( 1395): sensorservice died [0xaf0d99c0]
W/Sensors ( 4799): sensorservice died [0xaf0e2280]
W/Sensors ( 1767): sensorservice died [0xaf0a0640]
W/Sensors ( 1449): sensorservice died [0xaf0db340]
E/WifiManager( 1563): Channel connection lost
I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
F/libc    ( 6332): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c890 in tid 6332 (popupuireceiver)
,E/AndroidRuntime( 6312): Error reporting crash
E/AndroidRuntime( 6312): android.os.DeadObjectException
E/AndroidRuntime( 6312): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6312): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6312): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6312): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6312): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6312): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6312): Sending signal. PID: 6312 SIG: 9

```
