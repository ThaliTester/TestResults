#### Test 50242285e707819_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  295): DCD ON
,--------- beginning of system
E/Watchdog(  888): !@Sync 2
D/AndroidRuntime( 6047): 
D/AndroidRuntime( 6047): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6047): CheckJNI is OFF
D/AndroidRuntime( 6047): readGMSProperty: start
D/AndroidRuntime( 6047): readGMSProperty: already setted!!
D/AndroidRuntime( 6047): readGMSProperty: end
D/AndroidRuntime( 6047): addProductProperty: start
E/AffinityControl( 6047): AffinityControl: registerfunction enter
D/AndroidRuntime( 6047): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  888): inState():  stateMachine is null !!
I/PersonaManagerService(  888): PersonaId don't exist
I/ActivityManager(  888): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  888): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  888): Set to : 0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  888): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6062 uid=10267 gids={50267, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6062): MountEmulatedStorage()
E/Zygote  ( 6062): v2
I/libpersona( 6062): KNOX_SDCARD checking this for 10267
I/libpersona( 6062): KNOX_SDCARD not a persona
I/SELinux ( 6062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6062): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6047): Shutting down VM
D/TimaKeyStoreProvider( 6062): TimaSignature is unavailable
D/ActivityThread( 6062): Added TimaKeyStore provider
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  888): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  888): Display changed displayId=0
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SurfaceWidgetView( 1430): destroyHardwareResources():34445194
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6062): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1744): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1430): updateVisibility : ActivityRecord{129b503 token=android.os.BinderProxy@1003331f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1430): onTrimMemory. Level: 20
,I/WebViewFactory( 6062): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6062): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6062): Loading: webviewchromium
,I/LibraryLoader( 6062): Time to load native libraries: 6 ms (timestamps 6296-6302)
,I/LibraryLoader( 6062): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6062): Binding Chromium to main looper Looper (main, tid 1) {36a86e94}
,I/LibraryLoader( 6062): Expected native library version number "",actual native library version number ""
,I/chromium( 6062): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6062): Initializing chromium process, renderers=0
,W/art     ( 6062): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6062): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6062): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6062): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6062): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 6062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6062): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6062): Local Branch: mybranch5813579
I/Adreno-EGL( 6062): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6062): Local Patches: NONE
I/Adreno-EGL( 6062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/BluetoothAdapter( 6062): 836787517: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 6062): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6062): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6062): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6062): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6062): CordovaWebView is running on device made by: samsung
,W/art     ( 6062): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6062): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  888): Activity pause timeout for ActivityRecord{37097b5 u0 com.example.hello/.MainActivity t2}
,D/Activity( 6062): performCreate Call secproduct feature valuefalse
D/Activity( 6062): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6062): Render dirty regions requested: true
,D/Atlas   ( 6062): Validating map...
,D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
,V/ActivityThread( 6062): updateVisibility : ActivityRecord{120392e2 token=android.os.BinderProxy@150ea4c4 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/OpenGLRenderer( 6062): Initialized EGL, version 1.4
,D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6062): HWUI protection enabled for context ,  &this =0xb3c1eb28 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6062): Enabling debug mode 0
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SamsungIME( 1695): getCurrentCandidateView
,W/ActivityManager(  888): mDVFSHelper.release()
,I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{37097b5 u0 com.example.hello/.MainActivity t2} time:76846
,W/IInputConnectionWrapper( 6062): showStatusIcon on inactive InputConnection
I/Timeline( 6062): Timeline: Activity_idle id: android.os.BinderProxy@150ea4c4 time:76861
,D/SamsungIME( 1695): Dismiss ExpandCandiate
,I/chromium( 6062): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6062): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 6062): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6062): 
,D/JsMessageQueue( 6062): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1695): getDebugLevel  : 0x4f4c
,E/SMD     (  295): DCD ON
,I/SamsungIME( 1695): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1695): KeybaordView init() : load resources
,I/SamsungIME( 1695): getCurrentKeyboard
I/SamsungIME( 1695): getTextKeyboard
,D/jxcore_app_log( 6062): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358295296
,D/JX-Cordova( 6062): jxcore cordova android initializing
,D/SamsungIME( 1695): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 6062): Initializing JXcore engine
W/jxcore-log( 6062): JXcore engine is ready
,W/jxcore-log( 6062): Starting JXcore engine
,E/auditd  ( 1789): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  888): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  888): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  888): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6138 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6138): MountEmulatedStorage()
E/Zygote  ( 6138): v2
I/libpersona( 6138): KNOX_SDCARD checking this for 1000
I/libpersona( 6138): KNOX_SDCARD not a persona
,W/jxcore-log( 6062): Platform android
W/jxcore-log( 6062): 
W/jxcore-log( 6062): Process ARCH arm
W/jxcore-log( 6062): 
,I/jxcore-log( 6062): JXcore Cordova bridge is ready!
I/jxcore-log( 6062): 
W/jxcore-log( 6062): JXcore engine is started
,I/SELinux ( 6138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6138): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/jxcore-log( 6062): >> samsung-SM-N9005
E/jxcore-log( 6062): 
,I/jxcore-log( 6062): Total memory 2971471872
I/jxcore-log( 6062): 
I/jxcore-log( 6062): Free memory 429264896
I/jxcore-log( 6062): 
I/jxcore-log( 6062): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6062): 
I/jxcore-log( 6062): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6062): 
,I/jxcore-log( 6062): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6062): 
,I/jxcore-log( 6062): Size 1080 1920
I/jxcore-log( 6062): 
I/jxcore-log( 6062): Screen Brightness 162
I/jxcore-log( 6062): 
E/jxcore-log( 6062): Dummy Error Log.
E/jxcore-log( 6062): 
,D/TimaKeyStoreProvider( 6138): TimaSignature is unavailable
,D/ActivityThread( 6138): Added TimaKeyStore provider
,D/SamsungIME( 1695): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ResourcesManager( 6138): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6138):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6138):  SeDenialReceiver : File path = null
,I/ActivityManager(  888): Killing 5186:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6062): getBuffer is called!!!!
I/jxcore-log( 6062): 
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 30s ago
,D/SSRM:n  (  888): SIOP:: AP = 330, PST = 383, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  888): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/LightsService(  888): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 888) 
,D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/LightSensor(  888): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
D/SensorManager(  888): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
,E/SMD     (  295): DCD ON
,D/NtpTrustedTime(  888): forceRefresh() from cache miss
,D/NtpTrustedTime(  888): forceRefresh Fail.
,D/BatteryService(  888): turn on LED for fully charged
I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  888): showStatusBarByNotification() mOpenByNotification=false
,I/AudioService(  888): getStreamVolume 1 index 0
,D/NotificationService(  888): Noti Alert - doVibrate false convertStoV=true
,V/Vibrator(  888): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
,V/Vibrator(  888): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
V/Vibrator(  888): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
,D/VibratorService(  888): Turning vibrator off - ImmVibe.
,D/PowerManagerService(  888): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1185
,I/PowerManagerService(  888): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  888): Waking up from sleep (uid 10067)...
,D/PowerManagerService(  888): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate(  888): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@354effb7)
,D/KeyguardViewMediator( 1185): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1185): notifyScreenOnLocked
,D/PowerManagerService(  888): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController(  888): Blocking screen on until initial contents have been drawn.
,D/SContextService(  888): 	.registerCallback : 1, client=
,W/CAE     (  888): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,I/CAE     (  888): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
,D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/DisplayPowerController(  888): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
,I/CAE     (  888): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     (  888): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  888): sendAttribute() : service = Auto Rotation
,W/CAE     (  888): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  888): start(ContextProvider.java:126)
,V/CAE     (  888): clear(AutoRotationRunner.java:182)
,D/PowerManagerService(  888): [PWL] sb acquire: PowerManagerService.Display
D/AutomaticBrightnessController(  888): [api] [DAB] onSensorChanged : 1st lux : 1.2788
,D/AutomaticBrightnessController(  888): [DAB] updateAutoBrightnessSEC : 10(10.0)    0.0 < 1.2788 < 15.0 (0.0)
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
,I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 1
,D/SensorManager(  888): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/PowerManagerService(  888): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 20ms
E/Sensors (  888): Acc old sensor_state 512, new sensor_state : 513 en : 1
D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/MISC PowerHAL(  888): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService(  888): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  888): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/QCOM PowerHAL(  888): Got set_interactive hint
,V/CAE     (  888): enable(AutoRotationRunner.java:158)
I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  888): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs(  307): sendContextData: -79, 7, 0, 0
,D/SensorManager(  888): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  888): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 8ms
D/DisplayPowerController(  888): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  888): animation target = 10, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DisplayManagerService(  888): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
,D/CAE     (  888): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  888): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/DisplayPowerController(  888): getFinalBrightness : 10 -> 10
,D/DisplayPowerController(  888): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     (  888): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  888): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  888): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  888): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@25584d05, Service : AUTO_ROTATION(1)
W/CAE     (  888): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  888): addSContextService() : service = Auto Rotation
,D/SContextService(  888): ===== SContext Service List =====
D/SContextService(  888): Listener : android.hardware.scontext.SContextService$Listener@24ee815a, Service : Auto Rotation
D/SContextManager(  888):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@316d324, service=Auto Rotation
,V/ActivityManager(  888): Display changed displayId=0
,D/InputManager-JNI(  888): setDeviceInteractive: 1
,D/KeyguardViewMediator( 1185): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1185): onScreenTurnedOn()
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/SamsungIME( 1695): showDlgMsgBox : false true true
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,V/UserPresentBroadcastReceiver( 1485): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/NativeNfcManager( 1414): power state=4
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PalmMotion(  888): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
,D/PalmMotion(  888): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  888): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 888) 
D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
,D/SSRM:a  (  888): DeviceInfo:: 000000100000
D/SSRM:a  (  888): SettingsAirViewInfo:: 010100000
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
,D/NfcService( 1414): call the applyRotuiing
,D/LightsService(  888): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 888) 
,D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  888): turn off LED
D/LightsService(  888): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SensorManager(  888): unregisterListener ::   
D/lights  (  888): led_pattern : 0 +
D/lights  (  888): led_pattern : 0 -
,D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/KeyguardServiceDelegate(  888): **** SHOWN CALLED ****
D/StatusBarKeyguardViewManager( 1185): callback.onShown()
,D/DisplayPowerController(  888): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  888): Unblocked screen on after 201 ms
D/StatusBar.NetworkController( 1185): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/DisplayPowerState(  888): !@ ColorFade exit
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1185): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
,I/CAE     (  888): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  888): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  888): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  307): sendContextData: -76, 13, -47, 0
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (8/8)
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/8)
E/libEGL  (  888): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  888): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  888): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  (  888): lcd : 10 +
D/lights  (  888): lcd : 10 -
D/DisplayPowerController(  888): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  888): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  888): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService(  888): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  888): [input device light] handleInputDeviceLightOn
D/lights  (  888): button : 1 +
,D/InputMethodManagerService(  888): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  888):  handler : SCREEN_ON end
,D/BatteryMeterView( 1185): onDraw batteryColor : -1
,I/WifiNative-HAL(  888): startHal
,E/wifi    (  888): getStaticLongField sWifiHalHandle 0x9bdee80c
D/wifi    (  888): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x4014e6
I/WifiNative-HAL(  888): Could not start hal
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,D/NotificationService(  888): ACTION_SCREEN_ON
,D/LightsService(  888): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 888) 
D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  888): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  301): adev_set_parameters: enter: screen_state=on
V/voice   (  301): voice_set_parameters: enter: screen_state=on
V/voice   (  301): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  301): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  301): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  301): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  301): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  888): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/lights  (  888): button : 1 -
,D/IpRemoteDisplayController(  888): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  888): Bridge Server is not available
,I/Timeline( 6062): Timeline: Activity_idle id: android.os.BinderProxy@150ea4c4 time:80533
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
I/SurfaceFlinger(  254): id=12 createSurf (1080x750),1 flag=4, Ieads Up
,D/SurfaceControl(  888): Excessive delay in setPowerMode(): 257ms
D/PowerManagerService(  888): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 271ms
,D/GpsLocationProvider(  888): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  888): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  888): MSG_ACTION_SCREEN_ON called
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
,W/ResourcesManager(  888): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,I/NfcService( 1414): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1414): call the applyRotuiing
,D/accuweather( 1744): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
D/accuweather( 1744): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,I/SamsungIME( 1695): getNextShiftState() cursorCapsMode : 0
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25133852k
,D/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3296): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1449498972310
,D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/SSRM:n  (  888): SIOP:: AP = 330, PST = 377, CUR = 450
,D/PowerManagerService(  888): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3296): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3296): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3296): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3296): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 12/07/2015 09:07 PM
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 12/07/2015 03:36 PM
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3296): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/Finsky  ( 5446): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5446): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 1575): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:a  (  888): DeviceInfo:: 000000100000
D/SSRM:a  (  888): SettingsAirViewInfo:: 010100000,
,D/PowerManagerService(  888): [input device light] handleInputDeviceLightOff
,D/lights  (  888): button : 0 +
,D/lights  (  888): button : 0 -
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BluetoothAdapter( 6062): disable()
,E/BluetoothManagerService(  888): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6062): packageName : com.example.hello
,D/SecContentProvider(  888): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  888): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  888): mCursor = null
,D/WifiService(  888): setWifiEnabled: false pid=6062, uid=10267
,D/SettingsProvider(  888): name = wifi_on
,I/jxcore-log( 6062): ****TEST TOOK:  5063  ms ****
I/jxcore-log( 6062): 
,I/jxcore-log( 6062): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6062): 
,D/AndroidRuntime( 6204): 
D/AndroidRuntime( 6204): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6204): CheckJNI is OFF
,D/AndroidRuntime( 6204): readGMSProperty: start
,D/AndroidRuntime( 6204): readGMSProperty: already setted!!
,D/AndroidRuntime( 6204): readGMSProperty: end
,D/AndroidRuntime( 6204): addProductProperty: start
,E/SMD     (  295): DCD ON
,E/AffinityControl( 6204): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6204): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  888): START PACKAGE DELETE: observer{954171765}
D/PackageManager(  888): pkg{<packageName>}
D/PackageManager(  888): user{0}
D/PackageManager(  888): caller{2000}
D/PackageManager(  888): flags{3}
D/PersonaManagerService(  888): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  888): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  888): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  888): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  888): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  888): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  888): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  888): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  888): !@killApplicatoin: 10267, uninstall pkg
,I/ActivityManager(  888): Force stopping com.example.hello appid=10267 user=-1: uninstall pkg
I/ActivityManager(  888): Killing 6062:com.example.hello/u0a267 (adj 0): stop com.example.hello
,W/PackageSettings(  888): Skipping PackageSetting{22c064b4 com.test.thalitest/10266} due to missing metadata
,I/WindowState(  888): WIN DEATH: Window{1da6b923 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  888): Force removing ActivityRecord{37097b5 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,D/FocusedStackFrame(  888): Set to : 0
,D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  888): mDVFSHelper.acquire()
,V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  888): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/ActivityManager(  888): Display changed displayId=0
,D/SurfaceWidgetView( 1430): destroyHardwareResources():34445194
,D/Launcher( 1430): onRestart, Launcher: 435851321
,W/ActivityManager(  888): Spurious death for ProcessRecord{2619f50a 6062:com.example.hello/u0a267}, curProc for 6062: null
,I/ActivityManager(  888): Force stopping com.example.hello appid=10267 user=0: pkg removed
,I/art     ( 5853): Explicit concurrent mark sweep GC freed 2946(161KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 389us total 19.907ms
,I/art     ( 4281): Explicit concurrent mark sweep GC freed 8000(479KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 352us total 24.473ms
,D/Launcher( 1430): onStart, Launcher: 435851321
,D/Launcher.HomeView( 1430): onStart
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher( 1430): onResume, Launcher: 435851321
,D/SettingsProvider(  888): name = kids_home_mode
D/SettingsProvider(  888): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  888): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  888): selectionArgs: false
D/SettingsProvider(  888): selectionArgs: 10010
D/SecContentProvider(  888): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  888): ret = -1
,D/Launcher.HomeView( 1430): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1744): [237392/8] Surface widget resume on instance = 1
D/accuweather( 1744): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1744): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1744): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
,D/accuweather( 1744): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/Launcher( 1430): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1430): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,I/art     ( 4034): Explicit concurrent mark sweep GC freed 37735(2046KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 507us total 29.214ms
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/SamsungIME( 1695): mOCRHelper is null
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/accuweather( 1744): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,W/GeofencerStateMachine( 1485): Ignoring removeGeofence because network location is disabled.
,D/accuweather( 1744): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1744): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1744): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1744): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1744): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1744): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1744): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  ( 6234): MountEmulatedStorage()
E/Zygote  ( 6234): v2
I/libpersona( 6234): KNOX_SDCARD checking this for 10023
I/libpersona( 6234): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6234 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/accuweather( 1744): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,I/SELinux ( 6234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MenuAppsGridFragment( 1430): onResume
,D/comsamsunglog( 1744): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1744): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1744): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1744): [Accuweather J]>>> ==============================================================================================
,D/WallpaperManager( 1430): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1744): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/WallpaperManager( 1430): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1744): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1744): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/accuweather( 1744): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1744): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1744): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Mon, 7 December
,D/accuweather( 1744): [Accuweather J]>>> SM:2087 [0:0] makeTimeText[1] time :Mon, 7 December 15:35 , new :Mon, 7 December 15:36 
,D/accuweather( 1744): [Accuweather J]>>> SM:2208 [0:0] uCCV : msg = -1, oT = true
,D/accuweather( 1744): [Accuweather J]>>> SM:2171 [0:0] uCCV : time = 15:36
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ActivityManager(  888): handle home activity for 0
I/WallpaperManagerService(  888): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  888): post home show event for user 0
D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6234): TimaSignature is unavailable
,D/ActivityThread( 6234): Added TimaKeyStore provider
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager( 6234): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/SurfaceWidget.Renderer( 1744): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1744): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/Launcher( 1430): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1430): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,I/art     (  888): Explicit concurrent mark sweep GC freed 46276(3MB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 36MB/44MB, paused 3.946ms total 175.885ms
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/art     (  888): WaitForGcToComplete blocked for 118.437ms for cause Explicit
,I/KLMS-2.4.511: ( 6234): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.511: ( 6234): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449498975351
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,I/KLMS-2.4.511: ( 6234): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/KLMS-2.4.511: ( 6234): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/RegisteredServicesCache( 1414): empty dynamic service
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/InputMethodManagerService(  888): Got RemoteException sending setActive(false) notification to pid 6062 uid 10267
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MicrophoneInputStream( 1631): mic_starting gfk@24522f8
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/HotwordRecognitionRnr( 1631): Starting hotword detection.
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
V/AudioPolicyManager(  301): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  301): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  301): adev_open_input_stream: enter
E/audio_hw_primary(  301): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  301): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  301): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  301): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  301): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  301): adev_open_input_stream: exit
,I/AudioFlinger(  301): AudioFlinger's thread 0xb0856000 ready to run
V/audio_hw_primary(  301): in_standby: enter
V/audio_hw_primary(  301): in_standby: exit:  status(0)
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/EDMNativeHelperService(  888): isMicrophoneEnabled
V/audio_hw_primary(  301): in_standby: enter
V/audio_hw_primary(  301): in_standby: exit:  status(0)
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,V/AudioPolicyManager(  301): startInput() input 14
V/AudioPolicyManager(  301): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  301): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  301): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  301): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,V/audio_hw_primary(  301): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  301): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  301): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  301): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1631): mic_started gfk@24522f8
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
,V/msm8974_platform(  301): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  301): start_input_stream: enter: usecase(7)
V/voice   (  301): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  301): start_input_stream: usecase(7)
D/PreProcess(  301): new SamsungRecord
D/PreProcess(  301): new NS
I/samsungRecord(  301): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  301): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  301): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  301): 1
D/SamsungRecord_NS(  301): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  301): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  301): select_devices: ENTER
V/audio_hw_primary(  301): select_devices: usecase(normal)
V/audio_hw_primary(  301): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  301): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  301): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  301): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  301): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  301): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  301): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  301): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  301): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  301): ACDB -> send_adm_topology
D/ACDB-LOADER(  301): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ACDB-LOADER(  301): ACDB -> send_asm_topology
D/ACDB-LOADER(  301): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  301): ACDB -> send_audtable
D/ACDB-LOADER(  301): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  301): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  301): ACDB -> send_audvoltable
D/ACDB-LOADER(  301): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  301): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  301): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  301): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  301): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  301): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  301): ++++ audio_route_update_mixer ==============
D/audio_route(  301): Setting mixer control: ADC1 Volume
D/audio_route(  301): Setting mixer control: value: 19
,D/audio_route(  301): Setting mixer control: DEC6 Volume
D/audio_route(  301): Setting mixer control: value: 84
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/audio_route(  301): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  301): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  301): Setting mixer control: value: 1
,D/audio_route(  301): Setting mixer control: DEC6 MUX, value: 2
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/audio_route(  301): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  301): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  301): enable_audio_route: apply mixer path: audio-record
D/audio_route(  301): ++++ audio_route_update_mixer ==============
D/audio_route(  301): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  301): Setting mixer control: value: 1
,D/audio_route(  301): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  301): enable_audio_route: exit
V/audio_hw_primary(  301): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,D/WallpaperManager( 1430): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
V/audio_hw_primary(  301): start_input_stream: exit
,D/WallpaperManager( 1430): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/EnterpriseDeviceManagerService(  888): Package has changed for user 0
D/EnterpriseDeviceManagerService(  888): Admin package name: com.google.android.gms
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/Timeline( 1430): Timeline: Activity_idle id: android.os.BinderProxy@1003331f time:83894
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
E/Zygote  ( 6257): MountEmulatedStorage()
E/Zygote  ( 6257): v2
,I/libpersona( 6257): KNOX_SDCARD checking this for 10116
I/libpersona( 6257): KNOX_SDCARD not a persona
,I/HotwordWorker( 1631): onReady
,I/ActivityManager(  888): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6257 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/RCPManagerService(  888): PackageReceiver onReceive()
,I/HarmonyEASService(  888): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/ActivityManager(  888): Killing 5230:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/SELinux ( 6257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KnoxMUMContainerPolicy(  888): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/art     (  336): Explicit concurrent mark sweep GC freed 8765(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 310us total 13.469ms
,D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 9.852ms
,V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  888): uID is 10267
V/EnterpriseBillingPolicy(  888): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - end - null
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.733ms
,D/TaskPersister(  888): removeObsoleteFile: deleting file=2_task.xml
,D/WallpaperManagerService(  888):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  888): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
,D/TimaKeyStoreProvider( 6257): TimaSignature is unavailable
,D/ActivityThread( 6257): Added TimaKeyStore provider
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     (  888): Explicit concurrent mark sweep GC freed 7398(436KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 2.617ms total 231.713ms
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  888): mDVFSHelper.release()
D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager( 6257): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/PackageManager(  888): delete codoeFile: 
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/AASAUninstall(  888):  com.example.hello not target!
D/PackageManager(  888): result of delete: 1{954171765}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/AndroidRuntime( 6204): Shutting down VM
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14491( 6257): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/elm:14491( 6257): ELMEngine.ELMEngine( context ).
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6257): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/elm:14491( 6257): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14491( 6257): ElmAgentService : onCreate()
D/elm:14491( 6257): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6257): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6257): MDMBridge.getInstance()
D/elm:14491( 6257): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6257): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  ( 6274): MountEmulatedStorage()
I/libpersona( 6274): KNOX_SDCARD checking this for 10021
E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD not a persona
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/ActivityManager(  888): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6274 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
I/SELinux ( 6274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 6257): ElmAgentService : onDestroy().
I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  888): Killing 5038:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
W/ResourcesManager(  888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/TimaKeyStoreProvider( 6274): TimaSignature is unavailable
,D/ActivityThread( 6274): Added TimaKeyStore provider
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{3cffdfdf u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:84152
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager( 6274): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  888): clearDefaults: com.example.hello
,I/CrashAnrDetector(  888): onPackageRemoved : com.example.hello
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6274): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6274): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6274): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5697): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5697): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5697): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5697): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6290): MountEmulatedStorage()
E/Zygote  ( 6290): v2
I/libpersona( 6290): KNOX_SDCARD checking this for 10043
I/libpersona( 6290): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6290 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  888): Killing 4413:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 6290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6290): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 6290): TimaSignature is unavailable
,D/ActivityThread( 6290): Added TimaKeyStore provider
,D/ResourcesManager( 6290): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6290): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6290): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6290): PushLog.txt file is not deleted.
,D/SPPClientService( 6290): PushLog.txt file is not deleted.
D/SPPClientService( 6290): ============PushLog. stop!
,E/SQLiteLog( 6290): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6290): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6290): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6290): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6290): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6290): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6290): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6290): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6290): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6290): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6290): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6290): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6290): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/LNoti   ( 6290): [b] open fail. SQLException occured
,I/SA      ( 5784): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5784): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10267 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  888): Killing 5073:com.google.android.talk/u0a131 (adj 13): bgCount ##41
,I/EventHub(  888): Removing device '/dev/input/event6' due to inotify event
,E/SharedPreferencesImpl( 4826): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,I/EventHub(  888): Removing device '/dev/input/event7' due to inotify event
,D/Mms/FreeMessageReceiver( 4896): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  888): enable value -1
I/TactileAssist(  888): internal enable value -1
I/TactileAssist(  888): intensity value -1
I/TactileAssist(  888): saveAppList value true
,I/TactileAssist(  888): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4896): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4896): onHandleIntent: ACTION_PACKAGE_REMOVED
E/SharedPreferencesImpl(  888): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,D/SettingsProvider(  888): name = reading_mode_app_list
,D/Compatibility( 5810): onReceive() it will make start service
,D/Compatibility( 5810): onHandleIntent()
,D/Compatibility( 5810): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10267, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/UpdateIcingCorporaServi( 1631): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5810): found: 2
D/Compatibility( 5810): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5810): skipping ResolveInfo{35e7e000 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5810): considering ResolveInfo{19fa9039 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5810): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5810): enabling receiver ResolveInfo{2cb6f67e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{2c7587df com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{32eafc2c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5810): enabling receiver ResolveInfo{3ceaf6f5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SharedPreferencesImpl( 5810): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5810): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5810): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/EventHub(  888): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog( 1631): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1631): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1631): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa041e4e1 in tid 6310 (IntentService[U)
,W/ContextImpl( 5058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/RCPManager( 5357):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  888):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  888): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5058): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5058): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5058): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5058): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5058): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5058): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5058): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5058): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5058): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5058): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5058): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5058): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5058): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5058): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5058): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5058): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5058): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5058): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5058): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5058): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5058): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5058): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5058): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5058): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5058): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5058): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5058): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5058): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5058): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5058): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/EventHub(  888): Removing device '/dev/input/event9' due to inotify event
W/ContextImpl( 5853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6313): MountEmulatedStorage()
,E/Zygote  ( 6313): v2
I/libpersona( 6313): KNOX_SDCARD checking this for 10121
I/libpersona( 6313): KNOX_SDCARD not a persona
I/ActivityManager(  888): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6313 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/EventHub(  888): Removing device '/dev/input/event10' due to inotify event
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1631
,I/dumpstate( 6319): begin
,I/EventHub(  888): Removing device '/dev/input/event11' due to inotify event
,I/dumpstate( 6319): open lockfile failed No such file or directory
E/dumpstate( 6319): Cannot get free space size. So, skip dumpstate.
,I/SELinux ( 6313): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,I/EventHub(  888): Removing device '/dev/input/event12' due to inotify event
,E/audit_log( 1789): File locking failed. error= Bad file number
,D/TimaKeyStoreProvider( 6313): TimaSignature is unavailable
,D/ActivityThread( 6313): Added TimaKeyStore provider
,I/EventHub(  888): Removing device '/dev/input/event13' due to inotify event
,E/Zygote  ( 6330): MountEmulatedStorage()
E/Zygote  ( 6330): v2
I/libpersona( 6330): KNOX_SDCARD checking this for 1000
I/libpersona( 6330): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6330 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub(  888): Removing device '/dev/input/event14' due to inotify event
,I/SELinux ( 6330): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,E/SELinux ( 6330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Zygote  (  336): Process 1631 exited due to signal (7)
,D/ResourcesManager( 6313): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,V/AudioPolicyManager(  301): stopInput() input 14
V/AudioPolicyManager(  301): releaseInput() 14
V/AudioPolicyManager(  301): closeInput(14)
,D/TimaKeyStoreProvider( 6330): TimaSignature is unavailable
,D/ActivityThread( 6330): Added TimaKeyStore provider
,V/audio_hw_primary(  301): in_standby: enter
,W/ContextImpl( 6313): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6313): Unable to setupGraphicsSupport due to missing cache directory
,V/audio_hw_primary(  301): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  301): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  301): disable_audio_route: reset mixer path: audio-record
D/audio_route(  301): ++++ audio_route_update_mixer ==============
D/audio_route(  301): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  301): Setting mixer control: value: 0
,D/audio_route(  301): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  301): disable_audio_route: exit
V/audio_hw_primary(  301): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  301): ++++ audio_route_update_mixer ==============
D/audio_route(  301): Setting mixer control: ADC1 Volume
D/audio_route(  301): Setting mixer control: value: 0
D/audio_route(  301): Setting mixer control: DEC6 Volume
D/audio_route(  301): Setting mixer control: value: 0
,D/audio_route(  301): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  301): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  301): Setting mixer control: value: 0
,D/audio_route(  301): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  301): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  301): stop_input_stream: exit: status(0)
V/audio_hw_primary(  301): in_standby: exit:  status(0)
V/audio_hw_primary(  301): adev_close_input_stream
V/audio_hw_primary(  301): in_standby: enter
V/audio_hw_primary(  301): in_standby: exit:  status(0)
E/audio_hw_primary(  301): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  301): releaseInput() exit
,I/ActivityManager(  888): Process com.google.android.googlequicksearchbox:search (pid 1631)(adj 1) has died(492,1365)
,W/ActivityManager(  888): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  888): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
W/ActivityManager(  888): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 21000ms
,E/SQLiteLog( 6313): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6313): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6313): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6313): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
,E/SQLiteDatabase( 6313): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6313): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6313): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6313): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6313): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6313): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6313): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper( 6313): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6313): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6313): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 6313): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6313): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper( 6313): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteOpenHelper( 6313): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteOpenHelper( 6313): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 6313): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteLog( 6313): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6313): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6313): (14) os_unix.c:32503: (2) open(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db) - 
D/ResourcesManager( 6330): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,E/SQLiteDatabase( 6313): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6313): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/SQLiteDatabase( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6313): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 6313): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6313): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6313): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 6313): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 6313): Writing exception to parcel
E/DatabaseUtils( 6313): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:234)
E/DatabaseUtils( 6313): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/DatabaseUtils( 6313): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/DatabaseUtils( 6313): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/DatabaseUtils( 6313): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 6313): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 6313): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AndroidRuntime( 5853): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5853): Process: com.samsung.android.app.filterinstaller, PID: 5853
E/AndroidRuntime( 5853): android.database.sqlite.SQLiteException: unknown error (code 14): Could not open database
E/AndroidRuntime( 5853): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
E/AndroidRuntime( 5853): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 5853): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
E/AndroidRuntime( 5853): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/AndroidRuntime( 5853): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime( 5853): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromFS(FilterUninstaller.java:101)
E/AndroidRuntime( 5853): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:42)
E/AndroidRuntime( 5853): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5853): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ContextImpl( 6330): Unable to create files subdir /data/data/com.android.keychain/cache
E/ActivityThread( 6330): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  888): Killing 5328:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.filterinstaller
,E/AndroidRuntime(  888): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  888): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  888): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  888): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  888): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  888): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  888): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  888): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  888): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  888): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  888): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  888): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  888): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  888): 	... 5 more
,D/ResourcesManager(  888): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/PointerIcon(  888): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  888): setMouseCustomIcon IconType is same.101
D/PointerIcon(  888): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  888): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,F/libc    (  888): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa9766028 in tid 970 (ActivityManager)
,W/ContextImpl( 6330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2991 
,E/SQLiteLog( 6330): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6330): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6330): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6330): (14) os_unix.c:32503: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
,E/SQLiteDatabase( 6330): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6330): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6330): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6330): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6330): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6330): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase( 6330): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase( 6330): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6330): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6330): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 6330): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6330): Process: com.android.keychain, PID: 6330
E/AndroidRuntime( 6330): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6330): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6330): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6330): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6330): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime( 6330): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime( 6330): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6330): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6330): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,I/Process (  888): Sending signal. PID: 888 SIG: 9
,E/audit_log( 1789): File locking failed. error= Bad file number
,E/DEBUG   (  286): unexpected waitpid response: n=970, status=00000009
E/        (  286): ptrace detach from 970 failed: No such process
E/        (  286): debuggerd committing suicide to free the zombie!
,W/AudioFlinger(  301): power manager service died !!!
W/AudioCache(  301): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'tactileassist' died
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
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'cover' died
,I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'enterprise_policy' died
,I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
,I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'backup' died
,I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
,I/ServiceManager(  252): service 'samplingprofiler' died
I/ServiceManager(  252): service 'commontime_management' died
I/ServiceManager(  252): service 'dreams' died
I/ServiceManager(  252): service 'assetatlas' died
I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
,I/ServiceManager(  252): service 'media_router' died
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'wifi' died
,I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'connectivity' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'gfxinfo' died
,I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'entropy' died
,I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
,I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
,I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
,I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'cpuinfo' died
,I/SurfaceFlinger(  254): id=2 Removed GocusedStac (5/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
,I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (0/2)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (0/1)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (0/0)
E/AndroidRuntime( 6330): Error reporting crash
E/AndroidRuntime( 6330): android.os.DeadObjectException
E/AndroidRuntime( 6330): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6330): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6330): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6330): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6330): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6330): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (-2/0)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (-2/0)
W/Sensors ( 1918): sensorservice died [0xaf0d9a80]
W/Sensors ( 1185): sensorservice died [0xaf0da200]
,E/WifiManager( 1575): Channel connection lost
W/Sensors ( 1424): sensorservice died [0xaf0da280]
E/WifiManager( 1185): Channel connection lost
E/WifiManager( 1485): Channel connection lost
W/Sensors ( 1744): sensorservice died [0xaf0de3c0]
W/Sensors ( 1404): sensorservice died [0xaf0d8a00]
,W/Sensors ( 1485): sensorservice died [0xaf03d380]
,W/Sensors ( 4826): sensorservice died [0xaf042300]
,I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,E/WifiManager( 1324): Channel connection lost
,E/WifiManager( 1424): Channel connection lost
,W/Sensors ( 1430): sensorservice died [0xaf0da2c0]
,I/Process ( 6330): Sending signal. PID: 6330 SIG: 9
E/AndroidRuntime( 5853): Error reporting crash
E/AndroidRuntime( 5853): android.os.DeadObjectException
E/AndroidRuntime( 5853): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5853): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5853): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5853): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5853): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5853): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 5853): Sending signal. PID: 5853 SIG: 9
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
,E/installd(  304): eof
E/installd(  304): failed to read size
I/installd(  304): closing connection

```
