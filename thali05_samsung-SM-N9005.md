#### Test 5038801932cd575_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
I/ServiceManager(  356): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6077): 
D/AndroidRuntime( 6077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6077): CheckJNI is OFF
D/AndroidRuntime( 6077): readGMSProperty: start
D/AndroidRuntime( 6077): readGMSProperty: already setted!!
D/AndroidRuntime( 6077): readGMSProperty: end
D/AndroidRuntime( 6077): addProductProperty: start
E/AffinityControl( 6077): AffinityControl: registerfunction enter
D/AndroidRuntime( 6077): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  738): inState():  stateMachine is null !!
I/PersonaManagerService(  738): PersonaId don't exist
I/ActivityManager(  738): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  738): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  738): Set to : 0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  738): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6092 uid=10250 gids={50250, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 6092): MountEmulatedStorage()
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD checking this for 10250
I/libpersona( 6092): KNOX_SDCARD not a persona
I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6077): Shutting down VM
D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
D/ActivityThread( 6092): Added TimaKeyStore provider
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  738): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  738): Display changed displayId=0
D/SurfaceWidgetView( 1438): destroyHardwareResources():573502423
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6092): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
V/ActivityThread( 1438): updateVisibility : ActivityRecord{19020dac token=android.os.BinderProxy@301c0496 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1832): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1438): onTrimMemory. Level: 20
I/WebViewFactory( 6092): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6092): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6092): Loading: webviewchromium
I/LibraryLoader( 6092): Time to load native libraries: 5 ms (timestamps 9463-9468)
I/LibraryLoader( 6092): Expected native library version number "",actual native library version number ""
I/ServiceManager(  356): Waiting for service AtCmdFwd...
V/WebViewChromiumFactoryProvider( 6092): Binding Chromium to main looper Looper (main, tid 1) {b178d00}
I/LibraryLoader( 6092): Expected native library version number "",actual native library version number ""
I/chromium( 6092): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6092): Initializing chromium process, renderers=0
W/art     ( 6092): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6092): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6092): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6092): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6092): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/PowerManagerService(  738): [PWL] Off : 30s ago
D/BluetoothAdapter( 6092): 872233273: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6092): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6092): Local Branch: mybranch5813579
I/Adreno-EGL( 6092): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6092): Local Patches: NONE
I/Adreno-EGL( 6092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
V/AlarmManager(  738): waitForAlarm result :4
D/SSRM:n  (  738): SIOP:: AP = 330, PST = 388, CUR = 450
D/NtpTrustedTime(  738): forceRefresh() from cache miss
D/NtpTrustedTime(  738): forceRefresh Fail.
D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/LightsService(  738): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 738) 
D/LightsService(  738): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
E/LightSensor(  738): Light old sensor_state 0, new sensor_state : 512 en : 1
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
D/SecContentProvider2(  738): uri = 14 selection = getSealedState
D/SecContentProvider2(  738): mCursor = null
D/SensorManager(  738): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/BatteryService(  738): turn on LED for fully charged
D/ApplicationPolicy(  738): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  738): isApplicationStateBlocked userId -2 pkgname com.android.systemui
D/WindowManager(  738): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService(  738): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1183
I/PowerManagerService(  738): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  738): Waking up from sleep (uid 10067)...
D/PowerManagerService(  738): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  738): [s] UserActivityState : 0 -> 1
V/KeyguardServiceDelegate(  738): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2b36faf2)
D/PowerManagerService(  738): [PWL] sb acquire: PowerManagerService.Display
I/DisplayPowerController(  738): Blocking screen on until initial contents have been drawn.
D/SContextService(  738): 	.registerCallback : 1, client=
W/CAE     (  738): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
I/CAE     (  738): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
D/KeyguardViewMediator( 1183): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1183): notifyScreenOnLocked
I/CAE     (  738): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  738): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  738): sendAttribute() : service = Auto Rotation
W/CAE     (  738): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
D/InputManager-JNI(  738): setDeviceInteractive: 1
V/CAE     (  738): start(ContextProvider.java:126)
V/CAE     (  738): clear(AutoRotationRunner.java:182)
V/CAE     (  738): enable(AutoRotationRunner.java:158)
I/CAE     (  738): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  738): SendSensorHubData: send data = -79, 7, 0, 0
D/Sensorhubs(  301): sendContextData: -79, 7, 0, 0
D/InputManager-JNI(  738): sysfs_write +: /sys/class/input/event4/device/enabled: 1
D/AutomaticBrightnessController(  738): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/InputManager-JNI(  738): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/DisplayPowerController(  738): getFinalBrightness : 0 -> 0
D/MISC PowerHAL(  738): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/DisplayPowerController(  738): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/MISC PowerHAL(  738): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/AutomaticBrightnessController(  738): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/QCOM PowerHAL(  738): Got set_interactive hint
D/PowerManagerService(  738): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
I/AudioService(  738): getStreamVolume 1 index 0
D/AutomaticBrightnessController(  738): [api] [DAB] onSensorChanged : 1st lux : 2.0548
V/Vibrator(  738): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
D/AutomaticBrightnessController(  738): [DAB] updateAutoBrightnessSEC : 10(10.0)    0.0 < 2.0548 < 15.0 (0.0)
V/Vibrator(  738): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
D/AutomaticBrightnessController(  738): mCallbacks.updateBrightness()
V/Vibrator(  738): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
I/AutomaticBrightnessController(  738): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/AutomaticBrightnessController(  738): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/KeyguardViewMediator( 1183): handleNotifyScreenOn
D/NotificationService(  738): Noti Alert - doVibrate false convertStoV=true
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/VibratorService(  738): Turning vibrator off - ImmVibe.
I/AutomaticBrightnessController(  738): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 2
D/DisplayPowerController(  738): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  738): animation target = 10, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/KeyguardServiceDelegate(  738): **** SHOWN CALLED ****
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorManager(  738): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
I/DisplayManagerService(  738): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/Sensors (  738): Acc old sensor_state 512, new sensor_state : 513 en : 1
D/PalmMotion(  738): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/StatusBarKeyguardViewManager( 1183): onScreenTurnedOn()
D/PalmMotion(  738): SURFACE_PALM_SWIPE: 1
D/StatusBarKeyguardViewManager( 1183): callback.onShown()
D/PowerManagerService(  738): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 10ms
E/MotionRecognitionService(  738):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  738): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 738) 
W/chromium( 6092): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LightsService(  738): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/SSRM:a  (  738): DeviceInfo:: 000000100000
D/SSRM:a  (  738): SettingsAirViewInfo:: 010100000
V/ActivityManager(  738): Display changed displayId=0
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
W/chromium( 6092): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
V/UserPresentBroadcastReceiver( 1500): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/InputManager-JNI(  738): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  738): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/CAE     (  738): getFaultDetectionResult(AutoRotationRunner.java:195) - true
D/SensorManager(  738): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  738): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 17ms
I/CAE     (  738): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/SamsungIME( 1724): showDlgMsgBox : false true true
D/LightsService(  738): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 738) 
D/LightsService(  738): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  738): turn off LED
D/LightsService(  738): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/SensorManager(  738): unregisterListener ::   
D/lights  (  738): led_pattern : 0 +
D/lights  (  738): led_pattern : 0 -
D/LightsService(  738): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/NativeNfcManager( 1415): power state=4
W/art     ( 6092): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6092): onDetachedFromWindow called when already detached. Ignoring
D/NfcService( 1415): call the applyRotuiing
D/DisplayPowerController(  738): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  738): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1183): onDraw batteryColor : -1
I/CAE     (  738): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     (  738): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  738): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  738): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  301): sendContextData: -76, 13, -47, 0
D/SystemWebViewEngine( 6092): CordovaWebView is running on device made by: samsung
D/InputMethodManagerService(  738): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/MotionRecognitionService(  738):   mReceiver.onReceive : ACTION_SCREEN_ON
E/MotionRecognitionService(  738):  handler : SCREEN_ON end
D/CAE     (  738): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/WifiNative-HAL(  738): startHal
E/wifi    (  738): getStaticLongField sWifiHalHandle 0x9bead80c
D/wifi    (  738): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x401cfe
I/WifiNative-HAL(  738): Could not start hal
I/CAE     (  738): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
W/art     ( 6092): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6092): Attempt to remove local handle scope entry from IRT, ignoring
D/CAE     (  738): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  738): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@17249e43, Service : AUTO_ROTATION(1)
W/CAE     (  738): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  738): addSContextService() : service = Auto Rotation
D/SContextService(  738): ===== SContext Service List =====
D/SContextService(  738): Listener : android.hardware.scontext.SContextService$Listener@2da1fcc0, Service : Auto Rotation
D/SContextManager(  738):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@300ac543, service=Auto Rotation
D/DisplayPowerController(  738): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  738): Unblocked screen on after 96 ms
D/DisplayPowerState(  738): !@ ColorFade exit
D/NotificationService(  738): ACTION_SCREEN_ON
D/LightsService(  738): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 738) 
D/LightsService(  738): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  738): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  738): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/voice   (  295): voice_set_parameters: enter: screen_state=on
V/voice   (  295): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  295): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  295): adev_set_parameters: exit
I/SecExternalDisplayIntents_Java(  738): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
I/SurfaceFlinger(  254): id=8 Removed DolorFade (7/7)
I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/7)
E/libEGL  (  738): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  738): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  738): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  738): lcd : 10 +
D/lights  (  738): lcd : 10 -
D/DisplayPowerController(  738): getFinalBrightness : 10 -> 10
D/DisplayPowerController(  738): animation target = 10, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  738): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  738): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService(  738): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  738): [input device light] handleInputDeviceLightOn
D/lights  (  738): button : 1 +
D/IpRemoteDisplayController(  738): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  738): Bridge Server is not available
D/InputManager-JNI(  738): sysfs_write -: /sys/class/input/event4/device/enabled: 1
D/Activity( 6092): performCreate Call secproduct feature valuefalse
D/Activity( 6092): performCreate Call debug elastic valuetrue
D/KnoxNotification( 1183): ----- inflateViews : modified publicViewLocal -----
D/OpenGLRenderer( 6092): Render dirty regions requested: true
D/KnoxNotification( 1183): ----- inflateViews : modified KnoxViewLocal -----
D/lights  (  738): button : 1 -
D/Atlas   ( 6092): Validating map...
D/PersonaManager( 1183): PersonaID is invalid or persona doesn't exists. : 0
D/ActivityManager(  738): post active user change for 0
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
D/StatusBar.NetworkController( 1183): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1183): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
V/ActivityManager(  738): Display changed displayId=0
D/GpsLocationProvider(  738): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PersonaManagerService(  738): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  738): MSG_ACTION_SCREEN_ON called
I/NfcService( 1415): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1415): call the applyRotuiing
I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
I/SurfaceFlinger(  254): id=11 createSurf (1080x1920),1 flag=404, NainActivit
D/PowerManagerService(  738): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 257ms
D/SurfaceControl(  738): Excessive delay in setPowerMode(): 255ms
D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/OpenGLRenderer( 6092): Initialized EGL, version 1.4
I/SurfaceFlinger(  254): id=12 createSurf (1080x750),1 flag=4, Ieads Up
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6092): HWUI protection enabled for context ,  &this =0xb3b21b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6092): Enabling debug mode 0
D/ActivityManager(  738): post active user change for 0
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ActivityManager(  738): mDVFSHelper.release()
I/Timeline(  738): Timeline: Activity_windows_visible id: ActivityRecord{18556892 u0 com.example.hello/.MainActivity t2} time:79964
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
W/ResourcesManager(  738): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
I/SamsungIME( 1724): getCurrentCandidateView
D/InputManager-JNI(  738): sysfs_write -: /sys/class/input/event2/device/enabled: 1
I/Timeline( 6092): Timeline: Activity_idle id: android.os.BinderProxy@fa83630 time:79995
I/Timeline( 6092): Timeline: Activity_idle id: android.os.BinderProxy@fa83630 time:79995
D/accuweather( 1832): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
D/accuweather( 1832): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
E/AndroidProtocolHandler( 6092): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 6092): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1724): Dismiss ExpandCandiate
D/JsMessageQueue( 6092): Set native->JS mode to OnlineEventsBridgeMode
D/Finsky  ( 5438): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5438): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/SMD     (  287): DCD ON
I/chromium( 6092): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6092): 
I/SamsungIME( 1724): getDebugLevel  : 0x4f4c
I/SamsungIME( 1724): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1724): KeybaordView init() : load resources
D/jxcore_app_log( 6092): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357011968
D/JX-Cordova( 6092): jxcore cordova android initializing
I/SamsungIME( 1724): getCurrentKeyboard
I/SamsungIME( 1724): getTextKeyboard
D/SamsungIME( 1724): [SwiftkeyWrapper] currentLangauge : 1701729619
E/SQLiteLog( 1568): (10) POSIX Error : 11 SQLite Error : 3850
W/jxcore-log( 6092): Initializing JXcore engine
W/jxcore-log( 6092): JXcore engine is ready
D/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
E/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
W/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25132352k
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
I/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3304): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1448315197911
W/jxcore-log( 6092): Starting JXcore engine
D/PowerManagerService(  738): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:n  (  738): SIOP:: AP = 340, PST = 382, CUR = 450
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 3304): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3304): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3304): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3304): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 11/24/2015 02:20 AM
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 11/23/2015 10:46 PM
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3304): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
E/auditd  ( 1874): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  738): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  738): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6172): MountEmulatedStorage()
E/Zygote  ( 6172): v2
I/libpersona( 6172): KNOX_SDCARD checking this for 1000
I/libpersona( 6172): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6172 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ServiceManager(  356): Waiting for service AtCmdFwd...
E/SELinux ( 6172): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/jxcore-log( 6092): Platform android
W/jxcore-log( 6092): 
W/jxcore-log( 6092): Process ARCH arm
W/jxcore-log( 6092): 
D/TimaKeyStoreProvider( 6172): TimaSignature is unavailable
D/ActivityThread( 6172): Added TimaKeyStore provider
I/jxcore-log( 6092): JXcore Cordova bridge is ready!
I/jxcore-log( 6092): 
W/jxcore-log( 6092): JXcore engine is started
I/SamsungIME( 1724): getNextShiftState() cursorCapsMode : 0
D/ResourcesManager( 6172): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 6172):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6172):  SeDenialReceiver : File path = null
I/ActivityManager(  738): Killing 5190:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
E/jxcore-log( 6092): >> samsung-SM-N9005
E/jxcore-log( 6092): 
I/jxcore-log( 6092): Total memory 2971471872
I/jxcore-log( 6092): 
I/jxcore-log( 6092): Free memory 418353152
I/jxcore-log( 6092): 
I/jxcore-log( 6092): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6092): 
I/jxcore-log( 6092): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6092): 
I/jxcore-log( 6092): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6092): 
I/jxcore-log( 6092): Size 1080 1920
I/jxcore-log( 6092): 
I/jxcore-log( 6092): Screen Brightness 162
I/jxcore-log( 6092): 
E/jxcore-log( 6092): Dummy Error Log.
E/jxcore-log( 6092): 
D/SamsungIME( 1724): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SSRM:a  (  738): DeviceInfo:: 000000100000
,D/SSRM:a  (  738): SettingsAirViewInfo:: 010100000
,I/jxcore-log( 6092): getBuffer is called!!!!
I/jxcore-log( 6092): 
,D/PowerManagerService(  738): [input device light] handleInputDeviceLightOff
,D/lights  (  738): button : 0 +
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/lights  (  738): button : 0 -
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,I/ServiceManager(  356): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  356): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BluetoothAdapter( 6092): disable()
,E/BluetoothManagerService(  738): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6092): packageName : com.example.hello
,D/SecContentProvider(  738): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  738): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  738): mCursor = null
,D/WifiService(  738): setWifiEnabled: false pid=6092, uid=10250
,D/SettingsProvider(  738): name = wifi_on
,I/jxcore-log( 6092): ****TEST TOOK:  5079  ms ****
I/jxcore-log( 6092): 
,I/jxcore-log( 6092): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6092): 
,D/AndroidRuntime( 6221): 
D/AndroidRuntime( 6221): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6221): CheckJNI is OFF
,D/AndroidRuntime( 6221): readGMSProperty: start
D/AndroidRuntime( 6221): readGMSProperty: already setted!!
,D/AndroidRuntime( 6221): readGMSProperty: end
D/AndroidRuntime( 6221): addProductProperty: start
,E/SMD     (  287): DCD ON
,E/AffinityControl( 6221): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6221): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  738): START PACKAGE DELETE: observer{767945359}
D/PackageManager(  738): pkg{<packageName>}
D/PackageManager(  738): user{0}
D/PackageManager(  738): caller{2000}
D/PackageManager(  738): flags{3}
,D/PersonaManagerService(  738): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  738): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  738): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  738): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  738): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  738): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  738): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  738): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  738): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  738): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  738): !@killApplicatoin: 10250, uninstall pkg
,I/ActivityManager(  738): Force stopping com.example.hello appid=10250 user=-1: uninstall pkg
I/ActivityManager(  738): Killing 6092:com.example.hello/u0a250 (adj 0): stop com.example.hello
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/PackageSettings(  738): Skipping PackageSetting{34a15ed9 com.test.thalitest/10249} due to missing metadata
,I/WindowState(  738): WIN DEATH: Window{270a24ec u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=11 Removed NainActivit (-2/8)
,D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  738): Force removing ActivityRecord{18556892 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  738): Set to : 0
,D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  738): mDVFSHelper.acquire()
,V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  738): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,I/ActivityManager(  738): Force stopping com.example.hello appid=10250 user=0: pkg removed
,D/SurfaceWidgetView( 1438): destroyHardwareResources():573502423
,D/Launcher( 1438): onRestart, Launcher: 955400586
,D/Launcher( 1438): onStart, Launcher: 955400586
,D/Launcher.HomeView( 1438): onStart
,D/Launcher( 1438): onResume, Launcher: 955400586
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SettingsProvider(  738): name = kids_home_mode
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 10010
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,D/Launcher.HomeView( 1438): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1832): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1832): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
,D/accuweather( 1832): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1832): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1832): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/Launcher( 1438): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1438): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/accuweather( 1832): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,W/GeofencerStateMachine( 1500): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1832): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
E/SamsungIME( 1724): mOCRHelper is null
,D/accuweather( 1832): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
,D/accuweather( 1832): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1832): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
D/accuweather( 1832): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
,D/accuweather( 1832): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1832): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,I/InputReader(  738): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4260): Explicit concurrent mark sweep GC freed 7139(442KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 929us total 56.366ms
,E/Zygote  ( 6249): MountEmulatedStorage()
E/Zygote  ( 6249): v2
I/libpersona( 6249): KNOX_SDCARD checking this for 10023
I/libpersona( 6249): KNOX_SDCARD not a persona
,I/art     ( 5897): Explicit concurrent mark sweep GC freed 2946(161KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 350us total 78.575ms
I/art     ( 4025): Explicit concurrent mark sweep GC freed 36957(2013KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 425us total 56.510ms
,I/ActivityManager(  738): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6249 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager(  738): Spurious death for ProcessRecord{35a15125 6092:com.example.hello/u0a250}, curProc for 6092: null
,D/accuweather( 1832): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/SELinux ( 6249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/comsamsunglog( 1832): [Accuweather J]>>> ==============================================================================================
,D/comsamsunglog( 1832): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1832): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1832): [Accuweather J]>>> ==============================================================================================
,D/accuweather( 1832): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,D/accuweather( 1832): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/MenuAppsGridFragment( 1438): onResume
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/WallpaperManager( 1438): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1438): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/art     (  738): Explicit concurrent mark sweep GC freed 37192(2MB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 37MB/45MB, paused 2.870ms total 129.487ms
,I/art     (  738): WaitForGcToComplete blocked for 125.187ms for cause Explicit
,D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1832): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ActivityManager(  738): handle home activity for 0
,D/accuweather( 1832): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
I/WallpaperManagerService(  738): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  738): post home show event for user 0
D/ActivityManager(  738): post active user change for 0
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
D/accuweather( 1832): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1832): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Mon, 23 November
,D/SurfaceWidget.Renderer( 1832): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1832): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/TimaKeyStoreProvider( 6249): TimaSignature is unavailable
,D/ActivityThread( 6249): Added TimaKeyStore provider
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 6249): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 1438): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,W/ResourcesManager( 1438): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Launcher( 1438): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1438): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  738): Got RemoteException sending setActive(false) notification to pid 6092 uid 10250
,D/SecContentProvider2(  738): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  738): mCursor = null
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MicrophoneInputStream( 1593): mic_starting gfk@3f6886f3
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/HotwordRecognitionRnr( 1593): Starting hotword detection.
,V/AudioPolicyManager(  295): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  295): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  295): adev_open_input_stream: enter
E/audio_hw_primary(  295): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  295): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  295): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  295): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  295): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  295): adev_open_input_stream: exit
,I/AudioFlinger(  295): AudioFlinger's thread 0xb0556000 ready to run
V/audio_hw_primary(  295): in_standby: enter
V/audio_hw_primary(  295): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  738): isMicrophoneEnabled
,V/audio_hw_primary(  295): in_standby: enter
V/audio_hw_primary(  295): in_standby: exit:  status(0)
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,V/AudioPolicyManager(  295): startInput() input 14
V/AudioPolicyManager(  295): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  295): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  295): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  295): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,V/audio_hw_primary(  295): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  295): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  295): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  295): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 1593): mic_started gfk@3f6886f3
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/WallpaperManager( 1438): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/WallpaperManager( 1438): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/msm8974_platform(  295): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  295): start_input_stream: enter: usecase(7)
V/voice   (  295): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  295): start_input_stream: usecase(7)
D/PreProcess(  295): new SamsungRecord
D/PreProcess(  295): new NS
I/samsungRecord(  295): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  295): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  295): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  295): 1
D/SamsungRecord_NS(  295): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  295): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  295): select_devices: ENTER
V/audio_hw_primary(  295): select_devices: usecase(normal)
V/audio_hw_primary(  295): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  295): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  295): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  295): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  295): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  295): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  295): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  295): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  295): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  295): ACDB -> send_adm_topology
D/ACDB-LOADER(  295): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  295): ACDB -> send_asm_topology
D/ACDB-LOADER(  295): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  295): ACDB -> send_audtable
D/ACDB-LOADER(  295): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  295): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  295): ACDB -> send_audvoltable
D/ACDB-LOADER(  295): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  295): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  295): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  295): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  295): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  295): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  295): ++++ audio_route_update_mixer ==============
D/audio_route(  295): Setting mixer control: ADC1 Volume
D/audio_route(  295): Setting mixer control: value: 19
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/audio_route(  295): Setting mixer control: DEC6 Volume
D/audio_route(  295): Setting mixer control: value: 84
,D/audio_route(  295): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  295): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  295): Setting mixer control: value: 1
,D/audio_route(  295): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  295): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  295): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  295): enable_audio_route: apply mixer path: audio-record
D/audio_route(  295): ++++ audio_route_update_mixer ==============
D/audio_route(  295): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  295): Setting mixer control: value: 1
,D/audio_route(  295): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  295): enable_audio_route: exit
V/audio_hw_primary(  295): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  295): start_input_stream: exit
,I/KLMS-2.4.511: ( 6249): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/RegisteredServicesCache( 1415): empty dynamic service
,I/Timeline( 1438): Timeline: Activity_idle id: android.os.BinderProxy@301c0496 time:86775
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/EnterpriseDeviceManagerService(  738): Package has changed for user 0
D/EnterpriseDeviceManagerService(  738): Admin package name: com.google.android.gms
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/KLMS-2.4.511: ( 6249): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448315204375
,I/KLMS-2.4.511: ( 6249): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Books/Books.apk
,I/KLMS-2.4.511: ( 6249): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/HotwordWorker( 1593): onReady
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  738): PackageReceiver onReceive()
I/HarmonyEASService(  738): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  738): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  738): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  738): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  738): uID is 10250
V/EnterpriseBillingPolicy(  738): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  738): getProfileForApplication - enter
I/art     (  738): Explicit concurrent mark sweep GC freed 12790(747KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 1.955ms total 276.385ms
,V/EnterpriseBillingPolicyStorage(  738): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  738): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  738): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,E/Zygote  ( 6272): MountEmulatedStorage()
E/Zygote  ( 6272): v2
I/libpersona( 6272): KNOX_SDCARD checking this for 10116
I/libpersona( 6272): KNOX_SDCARD not a persona
,I/SELinux ( 6272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  738): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6272 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 5224:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/WallpaperManagerService(  738):  force update = false; persona id = 0; current user =0; current persona = 0
D/TaskPersister(  738): removeObsoleteFile: deleting file=2_task.xml
,D/KnoxTimeoutHandler(  738): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
,I/art     (  337): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 307us total 13.179ms
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 279us total 11.001ms
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  738): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 10.590ms
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider( 6272): TimaSignature is unavailable
,D/ActivityThread( 6272): Added TimaKeyStore provider
,D/PackageManager(  738): delete codoeFile: 
,I/AASAUninstall(  738):  com.example.hello not target!
,D/PackageManager(  738): result of delete: 1{767945359}
,D/AndroidRuntime( 6221): Shutting down VM
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 6272): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/Timeline(  738): Timeline: Activity_windows_visible id: ActivityRecord{76130df u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:87013
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/elm:14491( 6272): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491( 6272): ELMEngine.ELMEngine( context ).
,D/elm:14491( 6272): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/elm:14491( 6272): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/elm:14491( 6272): ElmAgentService : onCreate()
,D/elm:14491( 6272): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6272): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6272): MDMBridge.getInstance()
D/elm:14491( 6272): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6272): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  738): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  738): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  738): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6290): MountEmulatedStorage()
E/Zygote  ( 6290): v2
I/libpersona( 6290): KNOX_SDCARD checking this for 10021
I/libpersona( 6290): KNOX_SDCARD not a persona
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/ActivityManager(  738): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6290 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/SELinux ( 6290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 6272): ElmAgentService : onDestroy().
I/ActivityManager(  738): Killing 5031:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 6290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,E/SELinux ( 6290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  738): clearDefaults: com.example.hello
I/CrashAnrDetector(  738): onPackageRemoved : com.example.hello
,D/TimaKeyStoreProvider( 6290): TimaSignature is unavailable
,D/ActivityThread( 6290): Added TimaKeyStore provider
,D/ResourcesManager( 6290): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6290): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6290): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6290): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5745): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5745): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5745): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6307): MountEmulatedStorage()
,E/Zygote  ( 6307): v2
I/libpersona( 6307): KNOX_SDCARD checking this for 10043
I/libpersona( 6307): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6307 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 4354:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SELinux ( 6307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6307): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6307): TimaSignature is unavailable
,D/ActivityThread( 6307): Added TimaKeyStore provider
,D/ResourcesManager( 6307): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6307): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6307): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6307): PushLog.txt file is not deleted.
,D/SPPClientService( 6307): PushLog.txt file is not deleted.
D/SPPClientService( 6307): ============PushLog. stop!
,E/SQLiteLog( 6307): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6307): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6307): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6307): 	,at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6307): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6307): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6307): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6307): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6307): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6307): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6307): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6307): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6307): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6307): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6307): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6307): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6307): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6307): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/LNoti   ( 6307): [b] open fail. SQLException occured
,I/SA      ( 5831): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5831): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10250 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  738): Killing 5068:com.google.android.talk/u0a131 (adj 13): bgCount ##41
,E/SharedPreferencesImpl( 4858): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/Mms/FreeMessageReceiver( 4780): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  738): enable value -1
I/TactileAssist(  738): internal enable value -1
I/TactileAssist(  738): intensity value -1
I/TactileAssist(  738): saveAppList value true
,I/TactileAssist(  738): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4780): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4780): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/SettingsProvider(  738): name = reading_mode_app_list
,I/EventHub(  738): Removing device '/dev/input/event6' due to inotify event
,D/Compatibility( 5852): onReceive() it will make start service
,D/Compatibility( 5852): onHandleIntent()
,D/Compatibility( 5852): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10250, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5852): found: 2
D/Compatibility( 5852): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5852): skipping ResolveInfo{3eef2ff5 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
I/UpdateIcingCorporaServi( 1593): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5852): considering ResolveInfo{38f2418a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5852): default: com.sec.android.app.soundalive.SAControlPanelActivity
,W/ContextImpl( 5051): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 5852): enabling receiver ResolveInfo{9da23fb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5852): enabling receiver ResolveInfo{37f9fc18 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SQLiteLog( 5051): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
,E/SQLiteLog( 5051): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5051): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5051): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5051): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5051): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5051): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5051): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5051): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5051): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5051): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5051): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 5051): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5051): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5051): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5051): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5051): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5051): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5051): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
I/EventHub(  738): Removing device '/dev/input/event7' due to inotify event
W/System.err( 5051): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5051): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5051): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5051): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/RCPManager( 5345):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  738):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  738): queryAllProviders():  providerCallBack is not register for 0
D/Compatibility( 5852): enabling receiver ResolveInfo{12cfd671 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5852): enabling receiver ResolveInfo{223aec56 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SharedPreferencesImpl( 5852): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 5852): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5852): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/EventHub(  738): Removing device '/dev/input/event8' due to inotify event
W/ContextImpl( 5897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
E/SQLiteLog( 1593): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1593): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
F/libc    ( 1593): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04d24e1 in tid 6327 (IntentService[U)
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/EventHub(  738): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  ( 6330): MountEmulatedStorage()
E/Zygote  ( 6330): v2
I/libpersona( 6330): KNOX_SDCARD checking this for 10121
I/libpersona( 6330): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6330 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/DEBUG   (  283): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  283): failed to open /data/tombstones: No such file or directory
E/        (  283): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1593
,I/EventHub(  738): Removing device '/dev/input/event10' due to inotify event
,I/dumpstate( 6336): begin
,I/dumpstate( 6336): open lockfile failed No such file or directory
,E/dumpstate( 6336): Cannot get free space size. So, skip dumpstate.
,E/Zygote  ( 6337): MountEmulatedStorage()
,E/Zygote  ( 6337): v2
I/libpersona( 6337): KNOX_SDCARD checking this for 1000
I/libpersona( 6337): KNOX_SDCARD not a persona
,I/EventHub(  738): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 6330): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,I/ActivityManager(  738): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/audit_log( 1874): File locking failed. error= Bad file number
,I/EventHub(  738): Removing device '/dev/input/event12' due to inotify event
,I/SELinux ( 6337): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SELinux ( 6337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6330): TimaSignature is unavailable
,D/ActivityThread( 6330): Added TimaKeyStore provider
,I/EventHub(  738): Removing device '/dev/input/event13' due to inotify event
,D/TimaKeyStoreProvider( 6337): TimaSignature is unavailable
,D/ActivityThread( 6337): Added TimaKeyStore provider
,D/ResourcesManager( 6330): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,W/ContextImpl( 6330): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6330): Unable to setupGraphicsSupport due to missing cache directory
,D/ResourcesManager( 6337): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,W/ContextImpl( 6337): Unable to create files subdir /data/data/com.android.keychain/cache
,E/ActivityThread( 6337): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 6330): Shutting down VM
,E/AndroidRuntime( 6330): FATAL EXCEPTION: main
E/AndroidRuntime( 6330): Process: com.samsung.android.provider.filterprovider, PID: 6330
E/AndroidRuntime( 6330): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6330): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6330): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6330): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6330): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6330): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6330): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6330): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6330): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6330): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6330): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6330): 	... 11 more
E/AndroidRuntime( 6330): 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6330): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6330): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6330): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6330): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6330): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6330): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6330): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6330): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6330): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6330): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6330): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6330): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6330): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6330): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6330): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6330): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6330): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6330): 		at android.app.ActivityThread.handleBindAppl,ication(ActivityThread.java:5084)
E/AndroidRuntime( 6330): 		... 9 more
E/AndroidRuntime( 6330): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
E/AndroidRuntime( 6330): 		... 27 more
E/AndroidRuntime( 6330): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6330): 		... 27 more
E/AndroidRuntime( 6330): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6330): 		... 27 more
E/AndroidRuntime( 6330): 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
E/AndroidRuntime( 6330): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6330): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6330): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6330): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6330): 		... 13 more
E/AndroidRuntime( 6330): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
D/AndroidRuntime( 6337): Shutting down VM
V/AudioPolicyManager(  295): stopInput() input 14
V/AudioPolicyManager(  295): releaseInput() 14
V/AudioPolicyManager(  295): closeInput(14)
I/EventHub(  738): Removing device '/dev/input/event14' due to inotify event
E/AndroidRuntime( 6337): FATAL EXCEPTION: main
E/AndroidRuntime( 6337): Process: com.android.keychain, PID: 6337
E/AndroidRuntime( 6337): java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6337): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2972)
E/AndroidRuntime( 6337): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6337): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6337): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6337): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6337): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6337): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6337): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6337): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6337): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6337): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6337): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6337): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6337): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6337): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2967)
E/AndroidRuntime( 6337): 	... 9 more
E/AndroidRuntime( 6337): 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6337): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6337): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6337): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6337): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6337): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6337): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6337): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6337): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6337): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6337): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6337): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6337): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6337): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6337): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6337): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6337): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6337): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6337): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6337): 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6337): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6337): 		... 7 more
E/AndroidRuntime( 6337): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
E/AndroidRuntime( 6337): 		... 27 more
E/AndroidRuntime( 6337): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6337): 		... 27 more
E/AndroidRuntime( 6337): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6337): 		... 27 more
E/AndroidRuntime( 6337): 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
E/AndroidRuntime( 6337): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6337): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6337): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6337): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6337): 		... 11 more
E/AndroidRuntime( 6337): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/audio_hw_primary(  295): in_standby: enter
I/Zygote  (  337): Process 1593 exited due to signal (7)
I/ActivityManager(  738): Process com.google.android.googlequicksearchbox:search (pid 1593)(adj 1) has died(511,1360)
W/ActivityManager(  738): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  738): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  738): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.filterprovider
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,E/AndroidRuntime(  738): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  738): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  738): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  738): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  738): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  738): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  738): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  738): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  738): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  738): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  738): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  738): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  738): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  738): 	... 5 more
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
I/Process (  738): Sending signal. PID: 738 SIG: 9
V/audio_hw_primary(  295): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  295): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  295): disable_audio_route: reset mixer path: audio-record
D/audio_route(  295): ++++ audio_route_update_mixer ==============
D/audio_route(  295): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  295): Setting mixer control: value: 0
D/audio_route(  295): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  295): disable_audio_route: exit
V/audio_hw_primary(  295): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  295): ++++ audio_route_update_mixer ==============
D/audio_route(  295): Setting mixer control: ADC1 Volume
D/audio_route(  295): Setting mixer control: value: 0
D/audio_route(  295): Setting mixer control: DEC6 Volume
D/audio_route(  295): Setting mixer control: value: 0
D/audio_route(  295): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  295): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  295): Setting mixer control: value: 0
D/audio_route(  295): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  295): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  295): stop_input_stream: exit: status(0)
V/audio_hw_primary(  295): in_standby: exit:  status(0)
V/audio_hw_primary(  295): adev_close_input_stream
V/audio_hw_primary(  295): in_standby: enter
V/audio_hw_primary(  295): in_standby: exit:  status(0)
E/audio_hw_primary(  295): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  295): releaseInput() exit
,E/installd(  298): eof
E/installd(  298): failed to read size
I/installd(  298): closing connection
,W/Sensors ( 1183): sensorservice died [0xaf1dc200]
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
,D/SurfaceFlinger(  254): Screen type=0 is already mode=2
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
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
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
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
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_man,ager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'entropy' died
E/WifiManager( 1183): Channel connection lost
W/AudioFlinger(  295): power manager service died !!!
W/AudioCache(  295): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
W/Sensors ( 1897): sensorservice died [0xaf1d8a80]
W/Sensors ( 1500): sensorservice died [0xaf1a4380]
E/WifiManager( 1500): Channel connection lost
W/Sensors ( 1423): sensorservice died [0xaf1db280]
E/WifiManager( 1423): Channel connection lost
W/Sensors ( 1400): sensorservice died [0xaf1d9a00]
W/Sensors ( 1438): sensorservice died [0xaf1db340]
I/SurfaceFlinger(  254): id=13 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (4/7)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/7)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (5/6)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (5/5)
I/SurfaceFlinger(  254): id=13 Removed Mauncher (-2/5)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/5)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (2/4)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (2/3)
I/SurfaceFlinger(  254): id=12 Removed Ieads Up (-2/3)
W/Sensors ( 1832): sensorservice died [0xaf1a1640]
,W/Sensors ( 4858): sensorservice died [0xaf1e3240]
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (2/2)
,I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/1)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/0)
I/SurfaceFlinger(  254): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/0)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/0)
,E/WifiManager( 1312): Channel connection lost
E/WifiManager( 1568): Channel connection lost
E/AndroidRuntime( 6337): Error reporting crash
E/AndroidRuntime( 6337): android.os.DeadObjectException
E/AndroidRuntime( 6337): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6337): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6337): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6337): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6337): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6337): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/Process ( 6337): Sending signal. PID: 6337 SIG: 9
,E/ActivityThread( 5897): Failed to find provider info for com.samsung.android.provider.filterprovider
,E/ActivityThread( 5897): Failed to find provider info for com.samsung.android.provider.filterprovider
E/AndroidRuntime( 5897): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5897): Process: com.samsung.android.app.filterinstaller, PID: 5897
E/AndroidRuntime( 5897): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 5897): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 5897): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 5897): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 5897): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5897): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 6330): Error reporting crash
E/AndroidRuntime( 6330): android.os.DeadObjectException
E/AndroidRuntime( 6330): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6330): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6330): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6330): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6330): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6330): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6330): Sending signal. PID: 6330 SIG: 9
,E/AndroidRuntime( 5897): Error reporting crash
E/AndroidRuntime( 5897): android.os.DeadObjectException
E/AndroidRuntime( 5897): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5897): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5897): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5897): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5897): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5897): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 5897): Sending signal. PID: 5897 SIG: 9
,E/EsApplication( 5416): Uncaught exception in background thread Thread[IntentService[GPlusPackageMediaMonitor],5,main]
E/EsApplication( 5416): android.os.DeadObjectException
E/EsApplication( 5416): 	at android.os.BinderProxy.transactNative(Native Method)
E/EsApplication( 5416): 	at android.os.BinderProxy.transact(Binder.java:496)
E/EsApplication( 5416): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/EsApplication( 5416): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/EsApplication( 5416): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/EsApplication( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/EsApplication( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/EsApplication( 5416): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/EsApplication( 5416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/EsApplication( 5416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/EsApplication( 5416): 	at android.os.Looper.loop(Looper.java:145)
E/EsApplication( 5416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/EsApplication( 5416): Uncaught exception in background thread Thread[IntentService[GPlusPackageMediaMonitor],5,main]
E/EsApplication( 5416): java.lang.RuntimeException: Package manager has died
E/EsApplication( 5416): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:687)
E/EsApplication( 5416): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/EsApplication( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/EsApplication( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/EsApplication( 5416): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/EsApplication( 5416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/EsApplication( 5416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/EsApplication( 5416): 	at android.os.Looper.loop(Looper.java:145)
E/EsApplication( 5416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/EsApplication( 5416): Caused by: android.os.DeadObjectException
E/EsApplication( 5416): 	at android.os.BinderProxy.transactNative(Native Method)
E/EsApplication( 5416): 	at android.os.BinderProxy.transact(Binder.java:496)
E/EsApplication( 5416): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/EsApplication( 5416): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/EsApplication( 5416): 	... 8 more
E/AndroidRuntime( 5416): FATAL EXCEPTION: IntentService[GPlusPackageMediaMonitor]
E/AndroidRuntime( 5416): Process: com.google.android.apps.plus, PID: 5416
E/AndroidRuntime( 5416): android.os.DeadObjectException
E/AndroidRuntime( 5416): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5416): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5416): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentServices(IPackageManager.java:2865)
E/AndroidRuntime( 5416): 	at android.app.ApplicationPackageManager.queryIntentServicesAsUser(ApplicationPackageManager.java:681)
E/AndroidRuntime( 5416): 	at android.app.ApplicationPackageManager.queryIntentServices(ApplicationPackageManager.java:693)
E/AndroidRuntime( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.b(PG:165)
E/AndroidRuntime( 5416): 	at com.google.android.libraries.social.picasalegacy.PicasaStoreFacade.d(PG:280)
E/AndroidRuntime( 5416): 	at com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService.onHandleIntent(PG:78)
E/AndroidRuntime( 5416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5416): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5416): Error reporting crash
E/AndroidRuntime( 5416): android.os.DeadObjectException
E/AndroidRuntime( 5416): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5416): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5416): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5416): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5416): 	at ewf.run(PG:348)
E/AndroidRuntime( 5416): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5416): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5416): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5416): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 5416): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5416): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5416): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 5416): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
I/Process ( 5416): Sending signal. PID: 5416 SIG: 9
,I/SurfaceFlinger(  254): Disp[0] Orientation 0=>0
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
,E/qdhwcomposer(  254): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  254): eventControl(0, 1) failed Operation not permitted

```
