#### Test 503880194bce128_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{3ce9c0c0 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,--------- beginning of main
E/SMD     (  290): DCD ON
D/AndroidRuntime( 6119): 
D/AndroidRuntime( 6119): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6119): CheckJNI is OFF
D/AndroidRuntime( 6119): readGMSProperty: start
D/AndroidRuntime( 6119): readGMSProperty: already setted!!
D/AndroidRuntime( 6119): readGMSProperty: end
D/AndroidRuntime( 6119): addProductProperty: start
E/AffinityControl( 6119): AffinityControl: registerfunction enter
D/AndroidRuntime( 6119): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  905): inState():  stateMachine is null !!
I/PersonaManagerService(  905): PersonaId don't exist
I/ActivityManager(  905): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  905): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  905): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  905): Set to : 0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6135): MountEmulatedStorage()
E/Zygote  ( 6135): v2
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6135 uid=10256 gids={50256, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/libpersona( 6135): KNOX_SDCARD checking this for 10256
I/libpersona( 6135): KNOX_SDCARD not a persona
I/SELinux ( 6135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/PointerIcon(  905): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  905): setMouseCustomIcon IconType is same.101
D/PointerIcon(  905): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  905): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6119): Shutting down VM
E/SELinux ( 6135): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6135): TimaSignature is unavailable
D/ActivityThread( 6135): Added TimaKeyStore provider
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  905): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  905): Display changed displayId=0
D/SurfaceWidgetView( 1434): destroyHardwareResources():116651985
D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
D/ResourcesManager( 6135): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1434): updateVisibility : ActivityRecord{8223ade token=android.os.BinderProxy@216cb2aa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1434): onTrimMemory. Level: 20
I/WebViewFactory( 6135): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6135): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6135): Loading: webviewchromium
I/LibraryLoader( 6135): Time to load native libraries: 6 ms (timestamps 5425-5431)
I/LibraryLoader( 6135): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6135): Binding Chromium to main looper Looper (main, tid 1) {1c849f12}
I/LibraryLoader( 6135): Expected native library version number "",actual native library version number ""
I/chromium( 6135): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6135): Initializing chromium process, renderers=0
W/art     ( 6135): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6135): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6135): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6135): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6135): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 6135): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6135): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6135): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6135): Local Branch: mybranch5813579
I/Adreno-EGL( 6135): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6135): Local Patches: NONE
I/Adreno-EGL( 6135): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
D/BluetoothAdapter( 6135): 651912931: getState() :  mService = null. Returning STATE_OFF
E/Watchdog(  905): !@Sync 2
W/chromium( 6135): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6135): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6135): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6135): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager(  905): Activity pause timeout for ActivityRecord{272e63b u0 com.example.hello/.MainActivity t2}
D/SystemWebViewEngine( 6135): CordovaWebView is running on device made by: samsung
W/art     ( 6135): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6135): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6135): performCreate Call secproduct feature valuefalse
D/Activity( 6135): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6135): Render dirty regions requested: true
D/Atlas   ( 6135): Validating map...
D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
,V/ActivityThread( 6135): updateVisibility : ActivityRecord{3c358a10 token=android.os.BinderProxy@3daef0c2 {com.example.hello/com.example.hello.MainActivity}} show : true
I/SurfaceFlinger(  254): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  905): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  905): setMouseCustomIcon IconType is same.101
D/PointerIcon(  905): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  905): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6135): Initialized EGL, version 1.4
I/OpenGLRenderer( 6135): HWUI protection enabled for context ,  &this =0xb3c1f9e8 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6135): Enabling debug mode 0
D/InputMethodManagerService(  905): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  905): mDVFSHelper.release()
I/Timeline(  905): Timeline: Activity_windows_visible id: ActivityRecord{272e63b u0 com.example.hello/.MainActivity t2} time:76118
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 6135): showStatusIcon on inactive InputConnection
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 6135): Timeline: Activity_idle id: android.os.BinderProxy@3daef0c2 time:76137
I/SamsungIME( 1714): getCurrentCandidateView
D/SamsungIME( 1714): Dismiss ExpandCandiate
I/chromium( 6135): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6135): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 6135): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6135): 
D/JsMessageQueue( 6135): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1714): getDebugLevel  : 0x4f4c
I/SamsungIME( 1714): getDebugLevel  : 0x4f4c
I/SamsungIME( 1714): KeybaordView init() : load resources
D/jxcore_app_log( 6135): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357019520
D/JX-Cordova( 6135): jxcore cordova android initializing
I/SamsungIME( 1714): getCurrentKeyboard
I/SamsungIME( 1714): getTextKeyboard
D/SamsungIME( 1714): [SwiftkeyWrapper] currentLangauge : 1701729619
W/jxcore-log( 6135): Initializing JXcore engine
W/jxcore-log( 6135): JXcore engine is ready
W/jxcore-log( 6135): Starting JXcore engine
E/auditd  ( 1845): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  905): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  905): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6213): MountEmulatedStorage()
I/libpersona( 6213): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6213): v2
I/libpersona( 6213): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6213 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6135): Platform android
W/jxcore-log( 6135): 
,W/jxcore-log( 6135): Process ARCH arm
W/jxcore-log( 6135): 
,I/SELinux ( 6213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6213): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  344): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 913us total 40.534ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 486us total 20.937ms
,I/jxcore-log( 6135): JXcore Cordova bridge is ready!
I/jxcore-log( 6135): 
W/jxcore-log( 6135): JXcore engine is started
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 486us total 19.072ms
D/TimaKeyStoreProvider( 6213): TimaSignature is unavailable
D/ActivityThread( 6213): Added TimaKeyStore provider
,D/ResourcesManager( 6213): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6213):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6213):  SeDenialReceiver : File path = null
,I/ActivityManager(  905): Killing 5248:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,E/jxcore-log( 6135): >> samsung-SM-N9005
E/jxcore-log( 6135): 
,I/jxcore-log( 6135): Total memory 2971471872
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): Free memory 448540672
I/jxcore-log( 6135): 
I/jxcore-log( 6135): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): Size 1080 1920
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): Screen Brightness 162
I/jxcore-log( 6135): 
,E/jxcore-log( 6135): Dummy Error Log.
E/jxcore-log( 6135): 
,E/SMD     (  290): DCD ON
,D/SamsungIME( 1714): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 6135): getBuffer is called!!!!
I/jxcore-log( 6135): 
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/PowerManagerService(  905): [PWL] Off : 30s ago
,D/SSRM:n  (  905): SIOP:: AP = 370, PST = 418, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,V/AlarmManager(  905): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/BatteryService(  905): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  905): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  905): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/LightsService(  905): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 905) 
D/LightsService(  905): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/LightSensor(  905): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
D/BatteryService(  905): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  905): uri = 14 selection = getSealedState
,D/SecContentProvider2(  905): mCursor = null
,D/NtpTrustedTime(  905): forceRefresh() from cache miss
,D/NtpTrustedTime(  905): forceRefresh Fail.
,I/MotionRecognitionService(  905): Plugged
,D/ApplicationPolicy(  905): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  905): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,I/MotionRecognitionService(  905): setPowerConnected  = true
,D/SensorManager(  905): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  905): turn on LED for fully charged
,D/PowerManagerService(  905): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1190
,I/PowerManagerService(  905): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
,I/PowerManagerService(  905): Waking up from sleep (uid 10067)...
,D/WindowManager(  905): showStatusBarByNotification() mOpenByNotification=false
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@26777146)
,D/KeyguardViewMediator( 1190): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1190): notifyScreenOnLocked
D/PowerManagerService(  905): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  905): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController(  905): Blocking screen on until initial contents have been drawn.
,D/SContextService(  905): 	.registerCallback : 1, client=
,W/CAE     (  905): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/AutomaticBrightnessController(  905): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
,D/DisplayPowerController(  905): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  905): [DAB] setLightSensorEnabled : registerListener mLightSensor
,I/CAE     (  905): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,D/DisplayPowerController(  905): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
,I/CAE     (  905): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     (  905): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  905): sendAttribute() : service = Auto Rotation
,W/CAE     (  905): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  905): start(ContextProvider.java:126)
,D/SensorManager(  905): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/PowerManagerService(  905): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 12ms
,D/PowerManagerService(  905): [PWL] sb acquire: PowerManagerService.Display
,D/AutomaticBrightnessController(  905): [api] [DAB] onSensorChanged : 1st lux : 8.1354
,D/AutomaticBrightnessController(  905): [DAB] updateAutoBrightnessSEC : 20(20.0)    0.0 < 8.1354 < 17.0 (0.0)
E/Sensors (  905): Acc old sensor_state 512, new sensor_state : 513 en : 1
,D/AutomaticBrightnessController(  905): mCallbacks.updateBrightness()
,V/CAE     (  905): clear(AutoRotationRunner.java:182)
I/AutomaticBrightnessController(  905): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  905): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/AutomaticBrightnessController(  905): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 8
,V/CAE     (  905): enable(AutoRotationRunner.java:158)
,I/CAE     (  905): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  905): SendSensorHubData: send data = -79, 7, 0, 0
D/PowerManagerService(  905): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 10ms
D/SensorManager(  905): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  905): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  905): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  905): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/QCOM PowerHAL(  905): Got set_interactive hint
D/DisplayPowerController(  905): getFinalBrightness : 20 -> 20
D/DisplayPowerController(  905): animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Sensorhubs(  305): sendContextData: -79, 7, 0, 0
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/DisplayManagerService(  905): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/CAE     (  905): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  905): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/DisplayPowerController(  905): getFinalBrightness : 20 -> 20
,D/DisplayPowerController(  905): animation target = 20, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     (  905): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  905): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  905): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  905): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@281617da, Service : AUTO_ROTATION(1)
,W/CAE     (  905): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  905): addSContextService() : service = Auto Rotation
D/SContextService(  905): ===== SContext Service List =====
D/SContextService(  905): Listener : android.hardware.scontext.SContextService$Listener@1948c40b, Service : Auto Rotation
D/SContextManager(  905):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2782bf07, service=Auto Rotation
,D/KeyguardViewMediator( 1190): handleNotifyScreenOn
I/AudioService(  905): getStreamVolume 1 index 0
,D/NotificationService(  905): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  905): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
,D/StatusBarKeyguardViewManager( 1190): onScreenTurnedOn()
V/Vibrator(  905): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
V/Vibrator(  905): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
D/VibratorService(  905): Turning vibrator off - ImmVibe.
,D/StatusBar.NetworkController( 1190): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
,V/ActivityManager(  905): Display changed displayId=0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/DisplayPowerController(  905): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  905): Unblocked screen on after 126 ms
D/DisplayPowerState(  905): !@ ColorFade exit
,D/StatusBarKeyguardViewManager( 1190): callback.onShown()
,D/StatusBar.NetworkController( 1190): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
,D/NativeNfcManager( 1422): power state=4
,D/PalmMotion(  905): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
,D/PalmMotion(  905): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService(  905): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 905) 
D/LightsService(  905): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SamsungIME( 1714): showDlgMsgBox : false true true
,D/InputManager-JNI(  905): setDeviceInteractive: 1
,D/InputManager-JNI(  905): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/InputManager-JNI(  905): sysfs_write +: /sys/class/input/event2/device/enabled: 1,
,D/BatteryMeterView( 1190): onDraw batteryColor : -1
,D/InputManager-JNI(  905): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI(  905): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/SSRM:a  (  905): DeviceInfo:: 000000100000
D/SSRM:a  (  905): SettingsAirViewInfo:: 010100000
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (8/8)
,I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/8)
E/libEGL  (  905): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  905): getFinalBrightness : 20 -> 20
D/DisplayPowerController(  905): animation target = 20, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  905): lcd : 20 +
D/lights  (  905): lcd : 20 -
,V/UserPresentBroadcastReceiver( 1400): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/DisplayPowerController(  905): getFinalBrightness : 20 -> 20
D/DisplayPowerController(  905): animation target = 20, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  905): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  905): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService(  905): [input device light] setInputDeviceLightOn is called : 1
,D/NfcService( 1422): call the applyRotuiing
D/PowerManagerService(  905): [input device light] handleInputDeviceLightOn
D/lights  (  905): button : 1 +
D/lights  (  905): button : 1 -
,D/LightsService(  905): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 905) 
D/LightsService(  905): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/LightsService(  905): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SensorManager(  905): unregisterListener ::   
D/lights  (  905): led_pattern : 0 +
,D/lights  (  905): led_pattern : 0 -
D/LightsService(  905): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  905): turn off LED
,I/CAE     (  905): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  905): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  905): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  905): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  305): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService(  905): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  905):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  905):  handler : SCREEN_ON end
,D/KnoxNotification( 1190): ----- inflateViews : modified publicViewLocal -----
,D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
,D/KnoxNotification( 1190): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1190): PersonaID is invalid or persona doesn't exists. : 0
,I/WifiNative-HAL(  905): startHal
E/wifi    (  905): getStaticLongField sWifiHalHandle 0x9c4ff80c
D/wifi    (  905): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x70188a
I/WifiNative-HAL(  905): Could not start hal
,D/NotificationService(  905): ACTION_SCREEN_ON
D/LightsService(  905): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 905) 
D/LightsService(  905): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  905): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  905): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=on
V/voice   (  299): voice_set_parameters: enter: screen_state=on
V/voice   (  299): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  299): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  299): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  299): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  905): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  905): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  905): Bridge Server is not available
,D/InputManager-JNI(  905): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
,I/SurfaceFlinger(  254): id=12 createSurf (1080x750),1 flag=4, Ieads Up
D/SurfaceControl(  905): Excessive delay in setPowerMode(): 251ms
D/PowerManagerService(  905): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 257ms
,D/GpsLocationProvider(  905): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  905): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  905): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1422): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1422): call the applyRotuiing
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
,D/accuweather( 1776): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON,
D/accuweather( 1776): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,W/ResourcesManager(  905): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/Timeline( 6135): Timeline: Activity_idle id: android.os.BinderProxy@3daef0c2 time:80047
,I/SamsungIME( 1714): getNextShiftState() cursorCapsMode : 0
,D/InputManager-JNI(  905): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25130220k
,D/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3278): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1448461030847
,D/PowerManagerService(  905): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  (  905): SIOP:: AP = 360, PST = 411, CUR = 450
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3278): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3278): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3278): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3278): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 11/25/2015 04:18 PM
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 11/25/2015 03:17 PM
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3278): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/SMD     (  290): DCD ON
,D/Finsky  ( 5455): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5455): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 1544): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:a  (  905): DeviceInfo:: 000000100000
,D/SSRM:a  (  905): SettingsAirViewInfo:: 010100000
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService(  905): [input device light] handleInputDeviceLightOff
,D/lights  (  905): button : 0 +
,D/lights  (  905): button : 0 -
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BluetoothAdapter( 6135): disable()
,E/BluetoothManagerService(  905): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6135): packageName : com.example.hello
,D/SecContentProvider(  905): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  905): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  905): mCursor = null
,D/WifiService(  905): setWifiEnabled: false pid=6135, uid=10256
,D/SettingsProvider(  905): name = wifi_on
,I/jxcore-log( 6135): ****TEST TOOK:  5098  ms ****
I/jxcore-log( 6135): 
,I/jxcore-log( 6135): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6135): 
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6293): 
D/AndroidRuntime( 6293): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6293): CheckJNI is OFF
,D/AndroidRuntime( 6293): readGMSProperty: start
,D/AndroidRuntime( 6293): readGMSProperty: already setted!!
,D/AndroidRuntime( 6293): readGMSProperty: end
,D/AndroidRuntime( 6293): addProductProperty: start
,E/AffinityControl( 6293): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6293): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService(  905): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  905): START PACKAGE DELETE: observer{1066675082}
D/PackageManager(  905): pkg{<packageName>}
D/PackageManager(  905): user{0}
D/PackageManager(  905): caller{2000}
D/PackageManager(  905): flags{3}
D/PersonaManagerService(  905): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  905): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  905): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  905): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  905): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService(  905): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  905): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  905): getApplicationUninstallationEnabled
D/ApplicationPolicy(  905): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  905): !@killApplicatoin: 10256, uninstall pkg
,I/ActivityManager(  905): Force stopping com.example.hello appid=10256 user=-1: uninstall pkg
,I/ActivityManager(  905): Killing 6135:com.example.hello/u0a256 (adj 0): stop com.example.hello
,W/PackageSettings(  905): Skipping PackageSetting{10b1482 com.test.thalitest/10254} due to missing metadata
,I/WindowState(  905): WIN DEATH: Window{d74cc59 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,D/PointerIcon(  905): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  905): setMouseCustomIcon IconType is same.101
D/PointerIcon(  905): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  905): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  905): Force removing ActivityRecord{272e63b u0 com.example.hello/.MainActivity t2}: app died, no saved state
D/FocusedStackFrame(  905): Set to : 0
,D/CustomFrequencyManagerService(  905): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 905  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  905): mDVFSHelper.acquire()
,V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  905): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  905): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/ActivityManager(  905): Display changed displayId=0
,D/SurfaceWidgetView( 1434): destroyHardwareResources():116651985
,D/Launcher( 1434): onRestart, Launcher: 911445567
,W/ActivityManager(  905): Spurious death for ProcessRecord{2e16c5fb 6135:com.example.hello/u0a256}, curProc for 6135: null
,I/ActivityManager(  905): Force stopping com.example.hello appid=10256 user=0: pkg removed
D/Launcher( 1434): onStart, Launcher: 911445567
D/Launcher.HomeView( 1434): onStart
,D/Launcher( 1434): onResume, Launcher: 911445567
,D/SettingsProvider(  905): name = kids_home_mode
D/SettingsProvider(  905): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  905): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  905): selectionArgs: false
D/SettingsProvider(  905): selectionArgs: 10010
D/SecContentProvider(  905): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  905): ret = -1
D/Launcher.HomeView( 1434): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1776): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
,D/accuweather( 1776): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/Launcher( 1434): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/accuweather( 1776): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/Launcher( 1434): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1776): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/accuweather( 1776): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,D/accuweather( 1776): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1776): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1776): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
,D/accuweather( 1776): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
D/accuweather( 1776): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
,D/accuweather( 1776): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1776): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,D/ConnectivityService(  905): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1776): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
I/art     ( 4053): Explicit concurrent mark sweep GC freed 38526(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 459us total 26.527ms
,D/MenuAppsGridFragment( 1434): onResume
D/comsamsunglog( 1776): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1776): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
,D/comsamsunglog( 1776): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1776): [Accuweather J]>>> ==============================================================================================
,D/WallpaperManager( 1434): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1434): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1776): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,D/accuweather( 1776): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 1400): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
I/InputReader(  905): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4280): Explicit concurrent mark sweep GC freed 8802(513KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 417us total 30.616ms
,E/SamsungIME( 1714): mOCRHelper is null
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1776): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/accuweather( 1776): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1776): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1776): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Wed, 25 November
,D/accuweather( 1776): [Accuweather J]>>> SM:2087 [0:0] makeTimeText[1] time :Wed, 25 November 15:16 , new :Wed, 25 November 15:17 
,D/accuweather( 1776): [Accuweather J]>>> SM:2208 [0:0] uCCV : msg = -1, oT = true
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 5938): Explicit concurrent mark sweep GC freed 4529(228KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 353us total 24.601ms
,E/Zygote  ( 6322): MountEmulatedStorage()
E/Zygote  ( 6322): v2
I/libpersona( 6322): KNOX_SDCARD checking this for 10023
I/libpersona( 6322): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6322 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
D/ActivityManager(  905): handle home activity for 0
I/WallpaperManagerService(  905): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  905): post home show event for user 0
D/ActivityManager(  905): post active user change for 0
D/KnoxTimeoutHandler(  905): postActiveUserChange for user 0
,D/accuweather( 1776): [Accuweather J]>>> SM:2171 [0:0] uCCV : time = 15:17
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/SurfaceWidget.Renderer( 1776): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1776): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/art     (  905): Explicit concurrent mark sweep GC freed 44921(3MB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 37MB/45MB, paused 1.334ms total 125.838ms
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  905): WaitForGcToComplete blocked for 88.079ms for cause Explicit
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/PointerIcon(  905): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  905): setMouseCustomIcon IconType is same.101
D/PointerIcon(  905): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  905): setHoveringSpenCustomIcon IconType is same.1
,D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable
,D/ActivityThread( 6322): Added TimaKeyStore provider
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/EnterpriseDeviceManagerService(  905): Package has changed for user 0
D/EnterpriseDeviceManagerService(  905): Admin package name: com.google.android.gms
,D/ResourcesManager( 6322): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  905): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  905): mCursor = null
,D/Launcher( 1434): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/Launcher( 1434): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  905): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 6135 uid 10256
,D/RegisteredServicesCache( 1422): empty dynamic service
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/MicrophoneInputStream( 1633): mic_starting gfk@e93bd78
,V/AudioPolicyManager(  299): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  299): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  299): adev_open_input_stream: enter
E/audio_hw_primary(  299): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  299): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  299): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  299): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  299): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  299): adev_open_input_stream: exit
,I/AudioFlinger(  299): AudioFlinger's thread 0xb0f01000 ready to run
V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
,V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  905): isMicrophoneEnabled
,V/AudioPolicyManager(  299): startInput() input 14
I/HotwordRecognitionRnr( 1633): Starting hotword detection.
,V/AudioPolicyManager(  299): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  299): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  299): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  299): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,V/audio_hw_primary(  299): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  299): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  299): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  299): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1633): mic_started gfk@e93bd78
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/KLMS-2.4.511: ( 6322): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,V/msm8974_platform(  299): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  299): start_input_stream: enter: usecase(7)
V/voice   (  299): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  299): start_input_stream: usecase(7)
D/PreProcess(  299): new SamsungRecord
D/PreProcess(  299): new NS
I/samsungRecord(  299): [samsungrecord] SamsungRecInit 
D/WallpaperManager( 1434): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/samsungRecord(  299): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  299): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  299): 1
D/SamsungRecord_NS(  299): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  299): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  299): select_devices: ENTER
V/audio_hw_primary(  299): select_devices: usecase(normal)
V/audio_hw_primary(  299): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  299): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  299): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  299): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  299): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  299): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  299): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  299): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  299): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  299): ACDB -> send_adm_topology
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/WallpaperManager( 1434): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/ACDB-LOADER(  299): ACDB -> send_asm_topology
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  299): ACDB -> send_audtable
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  299): ACDB -> send_audvoltable
D/ACDB-LOADER(  299): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  299): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  299): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  299): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  299): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: ADC1 Volume
D/audio_route(  299): Setting mixer control: value: 19
,D/audio_route(  299): Setting mixer control: DEC6 Volume
D/audio_route(  299): Setting mixer control: value: 84
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/audio_route(  299): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  299): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  299): Setting mixer control: value: 1
,D/audio_route(  299): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  299): enable_audio_route: apply mixer path: audio-record
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  299): Setting mixer control: value: 1
,D/audio_route(  299): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  299): enable_audio_route: exit
V/audio_hw_primary(  299): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/audio_hw_primary(  299): start_input_stream: exit
,I/KLMS-2.4.511: ( 6322): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448461033908
,I/KLMS-2.4.511: ( 6322): MainReciver(): PACKAGE_REMOVED
,E/SMD     (  290): DCD ON
,I/KLMS-2.4.511: ( 6322): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/Timeline( 1434): Timeline: Activity_idle id: android.os.BinderProxy@216cb2aa time:83193
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/HotwordWorker( 1633): onReady
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,I/art     (  905): Explicit concurrent mark sweep GC freed 9590(576KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.750ms total 232.057ms
,E/Zygote  ( 6346): MountEmulatedStorage()
,E/Zygote  ( 6346): v2
I/libpersona( 6346): KNOX_SDCARD checking this for 10116
I/libpersona( 6346): KNOX_SDCARD not a persona
,I/ActivityManager(  905): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6346 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 5051:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux ( 6346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/SELinux ( 6346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  905): PackageReceiver onReceive()
I/HarmonyEASService(  905): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  905): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  905): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  905): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  905): uID is 10256
,V/EnterpriseBillingPolicy(  905): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  905): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  905): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  905): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  905): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage(  905): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService(  905):  force update = false; persona id = 0; current user =0; current persona = 0
,D/TaskPersister(  905): removeObsoleteFile: deleting file=2_task.xml
D/KnoxTimeoutHandler(  905): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler(  905): handleActiveUserChange for user 0
,D/TimaKeyStoreProvider( 6346): TimaSignature is unavailable
,D/ActivityThread( 6346): Added TimaKeyStore provider
,D/CustomFrequencyManagerService(  905): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 905  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  905): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  905): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 905  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/PackageManager(  905): delete codoeFile: 
,I/AASAUninstall(  905):  com.example.hello not target!
,D/PackageManager(  905): result of delete: 1{1066675082}
,D/AndroidRuntime( 6293): Shutting down VM
,D/ResourcesManager( 6346): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/elm:14491( 6346): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491( 6346): ELMEngine.ELMEngine( context ).
,D/elm:14491( 6346): MDMBridge.setEnterpriseBridge()
,D/elm:14491( 6346): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/elm:14491( 6346): ElmAgentService : onCreate()
,D/elm:14491( 6346): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6346): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6346): MDMBridge.getInstance()
D/elm:14491( 6346): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/elm:14491( 6346): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  ( 6363): MountEmulatedStorage()
E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD checking this for 10021
I/libpersona( 6363): KNOX_SDCARD not a persona
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  905): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6363 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,I/Timeline(  905): Timeline: Activity_windows_visible id: ActivityRecord{632525e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:83442
,W/ResourcesManager(  905): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/elm:14491( 6346): ElmAgentService : onDestroy().
,I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  905): Killing 4411:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/TimaKeyStoreProvider( 6363): TimaSignature is unavailable
,D/ActivityThread( 6363): Added TimaKeyStore provider
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 6363): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  905): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  905): clearDefaults: com.example.hello
,I/CrashAnrDetector(  905): onPackageRemoved : com.example.hello
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6363): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6363): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6363): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5770): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5770): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5770): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5770): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6379): MountEmulatedStorage()
E/Zygote  ( 6379): v2
I/libpersona( 6379): KNOX_SDCARD checking this for 10043
I/libpersona( 6379): KNOX_SDCARD not a persona
,I/SELinux ( 6379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6379): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  905): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6379 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  905): Killing 5089:com.google.android.talk/u0a131 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 6379): TimaSignature is unavailable
,D/ActivityThread( 6379): Added TimaKeyStore provider
,D/ResourcesManager( 6379): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/CustomFrequencyManagerService(  905): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 905  tag : ACTIVITY_RESUME_BOOSTER@11
,E/SPPClientService( 6379): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6379): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6379): PushLog.txt file is not deleted.
D/SPPClientService( 6379): PushLog.txt file is not deleted.
D/SPPClientService( 6379): ============PushLog. stop!
,W/FileUtils( 6379): Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/SA      ( 5863): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5863): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10256 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  905): Killing 5338:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/SharedPreferencesImpl( 4842): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/Mms/FreeMessageReceiver( 4913): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  905): enable value -1
I/TactileAssist(  905): internal enable value -1
I/TactileAssist(  905): intensity value -1
I/TactileAssist(  905): saveAppList value true
,I/TactileAssist(  905): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4913): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4913): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/SettingsProvider(  905): name = reading_mode_app_list
,D/Compatibility( 5885): onReceive() it will make start service
,D/Compatibility( 5885): onHandleIntent()
,I/EventHub(  905): Removing device '/dev/input/event6' due to inotify event
D/Compatibility( 5885): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10256, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5885): found: 2
D/Compatibility( 5885): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5885): skipping ResolveInfo{3c899a5e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5885): considering ResolveInfo{36538e3f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5885): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5885): enabling receiver ResolveInfo{1aa4f30c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5885): enabling receiver ResolveInfo{21915455 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 1633): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5885): enabling receiver ResolveInfo{2150fe6a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5885): enabling receiver ResolveInfo{cfccf5b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 5072): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,E/SharedPreferencesImpl( 5885): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5885): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5885): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/RCPManager( 5362):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  905):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  905): queryAllProviders():  providerCallBack is not register for 0
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
W/System.err( 5072): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5072): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5072): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5072): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5072): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5072): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5072): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5072): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5072): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5072): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5072): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/EventHub(  905): Removing device '/dev/input/event7' due to inotify event
W/ContextImpl( 5938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
E/SQLiteLog( 1633): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1633): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1633): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04d24e1 in tid 6400 (IntentService[U)
,I/EventHub(  905): Removing device '/dev/input/event8' due to inotify event
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6403): MountEmulatedStorage()
E/Zygote  ( 6403): v2
I/libpersona( 6403): KNOX_SDCARD checking this for 10121
I/libpersona( 6403): KNOX_SDCARD not a persona
,I/EventHub(  905): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  905): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6403 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6409): MountEmulatedStorage()
E/Zygote  ( 6409): v2
I/libpersona( 6409): KNOX_SDCARD checking this for 1000
I/libpersona( 6409): KNOX_SDCARD not a persona
,I/SELinux ( 6403): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6409 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub(  905): Removing device '/dev/input/event10' due to inotify event
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1633
,I/dumpstate( 6415): begin
,I/dumpstate( 6415): open lockfile failed No such file or directory
E/dumpstate( 6415): Cannot get free space size. So, skip dumpstate.
,I/EventHub(  905): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 6409): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SELinux ( 6409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6403): TimaSignature is unavailable
,D/ActivityThread( 6403): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6409): TimaSignature is unavailable
,D/ActivityThread( 6409): Added TimaKeyStore provider
,I/EventHub(  905): Removing device '/dev/input/event12' due to inotify event
,E/audit_log( 1845): File locking failed. error= Bad file number
,D/ResourcesManager( 6403): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/ResourcesManager( 6409): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,W/ContextImpl( 6409): Unable to create files subdir /data/data/com.android.keychain/cache
E/ActivityThread( 6409): Unable to setupGraphicsSupport due to missing cache directory
,W/ContextImpl( 6403): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6403): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 6409): Shutting down VM
,E/AndroidRuntime( 6409): FATAL EXCEPTION: main
E/AndroidRuntime( 6409): Process: com.android.keychain, PID: 6409
E/AndroidRuntime( 6409): java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6409): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2972)
E/AndroidRuntime( 6409): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6409): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6409): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6409): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6409): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6409): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6409): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6409): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6409): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2967)
E/AndroidRuntime( 6409): 	... 9 more
E/AndroidRuntime( 6409): 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6409): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6409): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6409): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6409): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6409): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6409): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6409): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6409): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6409): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6409): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6409): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6409): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6409): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6409): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6409): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6409): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6409): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6409): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6409): 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6409): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6409): 		... 7 more
E/AndroidRuntime( 6409): 	Caused ,by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
E/AndroidRuntime( 6409): 		... 27 more
E/AndroidRuntime( 6409): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6409): 		... 27 more
E/AndroidRuntime( 6409): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6409): 		... 27 more
E/AndroidRuntime( 6409): 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
E/AndroidRuntime( 6409): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6409): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6409): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6409): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6409): 		... 11 more
E/AndroidRuntime( 6409): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/EventHub(  905): Removing device '/dev/input/event13' due to inotify event
V/ApplicationPolicy(  905): isApplicationStateBlocked userId 0 pkgname com.android.keychain
E/AndroidRuntime(  905): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  905): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  905): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  905): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  905): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  905): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  905): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  905): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  905): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  905): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  905): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  905): 	... 5 more
D/ResourcesManager(  905): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/AndroidRuntime( 6403): Shutting down VM
,D/PointerIcon(  905): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/StatusBarManagerService(  905): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  905): setMouseCustomIcon IconType is same.101
D/PointerIcon(  905): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  905): setHoveringSpenCustomIcon IconType is same.1
,I/EventHub(  905): Removing device '/dev/input/event14' due to inotify event
,E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  905): checkUser: useridlist=null, currentuser=0
,F/libc    (  905): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa97b0028 in tid 987 (ActivityManager)
,E/AndroidRuntime( 6403): FATAL EXCEPTION: main
E/AndroidRuntime( 6403): Process: com.samsung.android.provider.filterprovider, PID: 6403
E/AndroidRuntime( 6403): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6403): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6403): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6403): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6403): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6403): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6403): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6403): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6403): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6403): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6403): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6403): 	... 11 more
E/AndroidRuntime( 6403): 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6403): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6403): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6403): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6403): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6403): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6403): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6403): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6403): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6403): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6403): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6403): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6403): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6403): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6403): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6403): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6403): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6403): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6403): 		at android.app.ActivityThread.handleBindAppl,ication(ActivityThread.java:5084)
E/AndroidRuntime( 6403): 		... 9 more
E/AndroidRuntime( 6403): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
E/AndroidRuntime( 6403): 		... 27 more
E/AndroidRuntime( 6403): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6403): 		... 27 more
E/AndroidRuntime( 6403): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6403): 		... 27 more
E/AndroidRuntime( 6403): 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
E/AndroidRuntime( 6403): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6403): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6403): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6403): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6403): 		... 13 more
E/AndroidRuntime( 6403): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/AudioPolicyManager(  299): stopInput() input 14
V/AudioPolicyManager(  299): releaseInput() 14
V/AudioPolicyManager(  299): closeInput(14)
E/Zygote  ( 6438): MountEmulatedStorage()
E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 1000
I/libpersona( 6438): KNOX_SDCARD not a persona
I/ActivityManager(  905): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/audio_hw_primary(  299): in_standby: enter
I/Zygote  (  344): Process 1633 exited due to signal (7)
,I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/audio_hw_primary(  299): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  299): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  299): disable_audio_route: reset mixer path: audio-record
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  299): Setting mixer control: value: 0
,D/audio_route(  299): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  299): disable_audio_route: exit
V/audio_hw_primary(  299): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  299): ++++ audio_route_update_mixer ==============
D/audio_route(  299): Setting mixer control: ADC1 Volume
D/audio_route(  299): Setting mixer control: value: 0
D/audio_route(  299): Setting mixer control: DEC6 Volume
D/audio_route(  299): Setting mixer control: value: 0
,D/audio_route(  299): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  299): Setting mixer control: AIF1_CAP Mixer SLIM TX7
,D/audio_route(  299): Setting mixer control: value: 0
,D/audio_route(  299): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  299): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  299): stop_input_stream: exit: status(0)
V/audio_hw_primary(  299): in_standby: exit:  status(0)
,V/audio_hw_primary(  299): adev_close_input_stream
V/audio_hw_primary(  299): in_standby: enter
V/audio_hw_primary(  299): in_standby: exit:  status(0)
E/audio_hw_primary(  299): adev_close_input_stream, set jack_in to null
,V/AudioPolicyManager(  299): releaseInput() exit
,D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
,D/ActivityThread( 6438): Added TimaKeyStore provider
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 905
,I/dumpstate( 6453): begin
,I/dumpstate( 6453): open lockfile failed No such file or directory
E/dumpstate( 6453): Cannot get free space size. So, skip dumpstate.
,E/libsuspend(  905): Error reading from /sys/power/wakeup_count: Interrupted system call
,E/audit_log( 1845): File locking failed. error= Bad file number
,E/installd(  302): eof
E/installd(  302): failed to read size
I/installd(  302): closing connection
,I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'connectivity' died
,I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
,I/ServiceManager(  252): service 'notification' died
I/ServiceManager(  252): service 'devicestoragemonitor' died
I/ServiceManager(  252): service 'location' died
I/ServiceManager(  252): service 'country_detector' died
,I/ServiceManager(  252): service 'search' died
I/ServiceManager(  252): service 'dropbox' died
,I/ServiceManager(  252): service 'wallpaper' died
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'wifi' died
,I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
,I/ServiceManager(  252): service 'enterprise_policy' died
E/ActivityThread( 5938): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'statusbar' died
,E/ActivityThread( 5938): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
,I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
,I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
,I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
I/ServiceManager(  252): service 'samplingprofiler' died
,I/ServiceManager(  252): service 'commontime_management' died
I/ServiceManager(  252): service 'dreams' died
I/ServiceManager(  252): service 'assetatlas' died
,I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
,I/ServiceManager(  252): service 'media_router' died
I/ServiceManager(  252): service 'trust' died
,I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
,I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'sec_analytics' died
,I/ServiceManager(  252): service 'backup' died
I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
,I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
,I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'context_aware' died
,I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
,I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'tactileassist' died
,I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
,I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
,I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
,I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'device_policy' died
,I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
,I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
,I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
,I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'scheduling_policy' died
,I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
,I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'permission' died
E/AndroidRuntime( 6409): Error reporting crash
E/AndroidRuntime( 6409): android.os.DeadObjectException
E/AndroidRuntime( 6409): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6409): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6409): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6409): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6409): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6409): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/Process ( 6409): Sending signal. PID: 6409 SIG: 9
E/AndroidRuntime( 5938): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5938): Process: com.samsung.android.app.filterinstaller, PID: 5938
E/AndroidRuntime( 5938): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 5938): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 5938): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 5938): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 5938): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5938): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'meminfo' died
E/AndroidRuntime( 5938): Error reporting crash
E/AndroidRuntime( 5938): android.os.DeadObjectException
E/AndroidRuntime( 5938): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5938): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5938): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5938): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5938): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5938): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/ServiceManager(  252): service 'procstats' died
,I/Process ( 5938): Sending signal. PID: 5938 SIG: 9
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
,I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
W/Sensors ( 4842): sensorservice died [0xaf1fe240]
E/WifiManager( 1544): Channel connection lost
,E/AndroidRuntime( 6403): Error reporting crash
E/AndroidRuntime( 6403): android.os.DeadObjectException
E/AndroidRuntime( 6403): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6403): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6403): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6403): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6403): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6403): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/Process ( 6403): Sending signal. PID: 6403 SIG: 9
W/Sensors ( 1416): sensorservice died [0xaf1c9a80]
E/WifiManager( 1400): Channel connection lost
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
E/WifiManager( 1428): Channel connection lost
,W/Sensors ( 1190): sensorservice died [0xaf1df200],
W/Sensors ( 1428): sensorservice died [0xaf1e42c0]
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (5/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
,I/SurfaceFlinger(  254): id=9 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
,W/Sensors ( 1934): sensorservice died [0xaf1c9a80]
W/Sensors ( 1776): sensorservice died [0xaf19c640]
W/AudioFlinger(  299): power manager service died !!!
W/AudioCache(  299): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
,I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (1/2)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (1/1)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (0/0),
E/WifiManager( 1190): Channel connection lost
,W/Sensors ( 1400): sensorservice died [0xaf115340]
,E/WifiManager( 1298): Channel connection lost
,I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
,I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
,I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (-2/0)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (-2/0)
,W/Sensors ( 1434): sensorservice died [0xaf118380]
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0

```
