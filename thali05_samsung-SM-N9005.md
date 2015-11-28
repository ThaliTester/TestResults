#### Test 50388019809f971_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  297): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6259): 
D/AndroidRuntime( 6259): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6259): CheckJNI is OFF
D/AndroidRuntime( 6259): readGMSProperty: start
D/AndroidRuntime( 6259): readGMSProperty: already setted!!
D/AndroidRuntime( 6259): readGMSProperty: end
D/AndroidRuntime( 6259): addProductProperty: start
E/AffinityControl( 6259): AffinityControl: registerfunction enter
D/AndroidRuntime( 6259): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  757): inState():  stateMachine is null !!
I/PersonaManagerService(  757): PersonaId don't exist
I/ActivityManager(  757): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  757): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  757): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  757): mDVFSHelper.acquire()
I/SurfaceFlinger(  256): id=9 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  256): id=10 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  757): Set to : 0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6276): MountEmulatedStorage()
I/libpersona( 6276): KNOX_SDCARD checking this for 10256
E/Zygote  ( 6276): v2
I/libpersona( 6276): KNOX_SDCARD not a persona
I/ActivityManager(  757): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6276 uid=10256 gids={50256, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/PointerIcon(  757): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/SELinux ( 6276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/PointerIcon(  757): setMouseCustomIcon IconType is same.101
D/PointerIcon(  757): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  757): setHoveringSpenCustomIcon IconType is same.1
E/SELinux ( 6276): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6259): Shutting down VM
D/TimaKeyStoreProvider( 6276): TimaSignature is unavailable
D/ActivityThread( 6276): Added TimaKeyStore provider
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  757): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  757): Display changed displayId=0
D/SurfaceWidgetView( 1440): destroyHardwareResources():993080641
D/ConnectivityService(  757): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6276): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  256): id=7 Removed Mauncher (6/8)
I/SurfaceFlinger(  256): id=7 Removed Mauncher (-2/8)
V/ActivityThread( 1440): updateVisibility : ActivityRecord{1a163d8e token=android.os.BinderProxy@368ea05a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1440): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1779): [237392/8] Surface widget visibility changed visibility = false on instance = 1
,I/WebViewFactory( 6276): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6276): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6276): Loading: webviewchromium
,I/LibraryLoader( 6276): Time to load native libraries: 8 ms (timestamps 9259-9267)
I/LibraryLoader( 6276): Expected native library version number "",actual native library version number ""
,V/AlarmManager(  757): waitForAlarm result :4
,D/NtpTrustedTime(  757): forceRefresh() from cache miss,
,D/NtpTrustedTime(  757): forceRefresh Fail.
,D/BatteryService(  757): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  757): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  757): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/LightsService(  757): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 757) 
D/BatteryService(  757): Sending ACTION_BATTERY_CHANGED.
,D/LightsService(  757): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,V/WebViewChromiumFactoryProvider( 6276): Binding Chromium to main looper Looper (main, tid 1) {1119b6c2}
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
I/LibraryLoader( 6276): Expected native library version number "",actual native library version number ""
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/chromium( 6276): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SecContentProvider2(  757): uri = 14 selection = getSealedState
D/SecContentProvider2(  757): mCursor = null
,E/LightSensor(  757): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/MotionRecognitionService(  757): Plugged
I/MotionRecognitionService(  757): setPowerConnected  = true
,D/SensorManager(  757): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  757): turn on LED for fully charged
,I/BrowserStartupController( 6276): Initializing chromium process, renderers=0
,D/ApplicationPolicy(  757): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
V/ApplicationPolicy(  757): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  757): showStatusBarByNotification() mOpenByNotification=false
,I/AudioService(  757): getStreamVolume 1 index 0
D/NotificationService(  757): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  757): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
V/Vibrator(  757): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
D/PowerManagerService(  757): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1186
I/PowerManagerService(  757): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  757): Waking up from sleep (uid 10067)...
V/Vibrator(  757): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
D/VibratorService(  757): Turning vibrator off - ImmVibe.
D/PowerManagerService(  757): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate(  757): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@31fdfe34)
D/PowerManagerService(  757): [s] UserActivityState : 0 -> 1
D/PowerManagerService(  757): [PWL] sb acquire: PowerManagerService.Display
D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController(  757): Blocking screen on until initial contents have been drawn.
D/SContextService(  757): 	.registerCallback : 1, client=
D/KeyguardViewMediator( 1186): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1186): notifyScreenOnLocked
W/CAE     (  757): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
I/CAE     (  757): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  757): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  757): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  757): sendAttribute() : service = Auto Rotation
W/CAE     (  757): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  757): start(ContextProvider.java:126)
V/CAE     (  757): clear(AutoRotationRunner.java:182)
V/CAE     (  757): enable(AutoRotationRunner.java:158)
D/AutomaticBrightnessController(  757): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  757): getFinalBrightness : 0 -> 0
D/AutomaticBrightnessController(  757): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/DisplayPowerController(  757): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/PowerManagerService(  757): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  757): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  757): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/CAE     (  757): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  757): SendSensorHubData: send data = -79, 7, 0, 0
I/QCOM PowerHAL(  757): Got set_interactive hint
D/Sensorhubs(  311): sendContextData: -79, 7, 0, 0
D/InputManager-JNI(  757): setDeviceInteractive: 1
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CAE     (  757): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  757): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/AutomaticBrightnessController(  757): [api] [DAB] onSensorChanged : 1st lux : 16.8672
,D/AutomaticBrightnessController(  757): [DAB] updateAutoBrightnessSEC : 44(44.0)    0.0 < 16.8672 < 41.0 (0.0)
D/AutomaticBrightnessController(  757): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  757): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
,I/AutomaticBrightnessController(  757): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 2
D/InputManager-JNI(  757): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  757): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,I/AutomaticBrightnessController(  757): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 16
D/InputManager-JNI(  757): sysfs_write +: /sys/class/input/event4/device/enabled: 1
,D/DisplayPowerController(  757): getFinalBrightness : 44 -> 44
D/DisplayPowerController(  757): animation target = 44, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/DisplayManagerService(  757): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorManager(  757): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/PowerManagerService(  757): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 21ms
,E/Sensors (  757): Acc old sensor_state 512, new sensor_state : 513 en : 1
,D/InputManager-JNI(  757): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,W/ActivityManager(  757): Activity pause timeout for ActivityRecord{196de92c u0 com.example.hello/.MainActivity t2}
,D/KeyguardViewMediator( 1186): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 1186): onScreenTurnedOn()
,D/LightsService(  757): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 757) 
D/LightsService(  757): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  757): turn off LED
,D/LightsService(  757): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SSRM:n  (  757): SIOP:: AP = 330, PST = 388, CUR = 450
,D/SensorManager(  757): unregisterListener ::   
D/lights  (  757): led_pattern : 0 +
D/lights  (  757): led_pattern : 0 -
D/LightsService(  757): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SensorManager(  757): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  757): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 13ms
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb6962000
,D/qdhwcomposer(  256): hwc_blank: Unblanking display: 0
,W/chromium( 6276): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6276): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6276): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6276): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/DisplayPowerController(  757): getFinalBrightness : 44 -> 44
D/DisplayPowerController(  757): animation target = 44, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     (  757): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  757): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  757): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/ServiceManager(  335): Waiting for service AtCmdFwd...
I/CAE     (  757): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@a8834d7, Service : AUTO_ROTATION(1)
W/CAE     (  757): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  757): addSContextService() : service = Auto Rotation
D/SContextService(  757): ===== SContext Service List =====
D/SContextService(  757): Listener : android.hardware.scontext.SContextService$Listener@316231c4, Service : Auto Rotation
D/SContextManager(  757):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3cd1445d, service=Auto Rotation
,D/BluetoothAdapter( 6276): 967711955: getState() :  mService = null. Returning STATE_OFF
,D/KnoxNotification( 1186): ----- inflateViews : modified publicViewLocal -----
,V/ActivityManager(  757): Display changed displayId=0
,I/Adreno-EGL( 6276): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6276): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6276): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6276): Local Branch: mybranch5813579
I/Adreno-EGL( 6276): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6276): Local Patches: NONE
I/Adreno-EGL( 6276): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/KnoxNotification( 1186): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1186): PersonaID is invalid or persona doesn't exists. : 0
,D/NativeNfcManager( 1417): power state=4
,D/NfcService( 1417): call the applyRotuiing
,D/SamsungIME( 1719): showDlgMsgBox : false true true
,V/UserPresentBroadcastReceiver( 1479): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/talkback/talkback.apk
,V/KeyguardServiceDelegate(  757): **** SHOWN CALLED ****
D/DisplayPowerController(  757): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  757): Unblocked screen on after 129 ms
D/DisplayPowerState(  757): !@ ColorFade exit
,D/StatusBarKeyguardViewManager( 1186): callback.onShown()
D/StatusBar.NetworkController( 1186): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/PalmMotion(  757): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/MotionRecognitionService(  757):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/PalmMotion(  757): SURFACE_PALM_SWIPE: 1
D/LightsService(  757): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 757) 
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=false enabledDesc:null
D/LightsService(  757): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/StatusBar.NetworkController( 1186): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/LightsService(  757): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/LightsService(  757): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRM:a  (  757): DeviceInfo:: 000000100000
,D/SSRM:a  (  757): SettingsAirViewInfo:: 010100000
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=false enabledDesc:null
,I/SurfaceFlinger(  256): id=8 Removed DolorFade (7/7)
,I/SurfaceFlinger(  256): id=8 Removed DolorFade (-2/7)
E/libEGL  (  757): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  757): getFinalBrightness : 44 -> 44
D/DisplayPowerController(  757): animation target = 44, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  (  757): lcd : 44 +
D/lights  (  757): lcd : 44 -
D/DisplayPowerController(  757): getFinalBrightness : 44 -> 44
D/DisplayPowerController(  757): animation target = 44, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  757): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  757): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  757): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  757): [input device light] handleInputDeviceLightOn
D/lights  (  757): button : 1 +
,D/InputManager-JNI(  757): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,I/CAE     (  757): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  757): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  757): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  757): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  311): sendContextData: -76, 13, -47, 0
D/BatteryMeterView( 1186): onDraw batteryColor : -1
,D/InputMethodManagerService(  757): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  757):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  757):  handler : SCREEN_ON end
,I/WifiNative-HAL(  757): startHal
,E/wifi    (  757): getStaticLongField sWifiHalHandle 0x9baff80c
D/wifi    (  757): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x401d42
I/WifiNative-HAL(  757): Could not start hal
,D/NotificationService(  757): ACTION_SCREEN_ON
D/LightsService(  757): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 757) 
D/LightsService(  757): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  757): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  757): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/lights  (  757): button : 1 -
,D/audio_hw_primary(  305): adev_set_parameters: enter: screen_state=on
V/voice   (  305): voice_set_parameters: enter: screen_state=on
V/voice   (  305): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  305): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  305): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  305): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  305): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  757): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,W/chromium( 6276): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6276): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/InputManager-JNI(  757): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6276): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6276): CordovaWebView is running on device made by: samsung
,W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6276): Attempt to remove local handle scope entry from IRT, ignoring
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  256): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  256): hwc_blank: Done unblanking display: 0
,I/SurfaceFlinger(  256): id=11 createSurf (1080x750),1 flag=4, Ieads Up
D/SurfaceControl(  757): Excessive delay in setPowerMode(): 261ms
D/PowerManagerService(  757): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 286ms
,D/IpRemoteDisplayController(  757): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  757): Bridge Server is not available
,D/Activity( 6276): performCreate Call secproduct feature valuefalse
D/Activity( 6276): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6276): Render dirty regions requested: true
,D/Atlas   ( 6276): Validating map...
,D/ActivityManager(  757): post active user change for 0
D/KnoxTimeoutHandler(  757): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  757): handleActiveUserChange for user 0
,D/GpsLocationProvider(  757): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  757): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  757): MSG_ACTION_SCREEN_ON called
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
,W/ResourcesManager(  757): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,I/NfcService( 1417): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1417): call the applyRotuiing
,D/ActivityManager(  757): post active user change for 0
D/KnoxTimeoutHandler(  757): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  757): handleActiveUserChange for user 0
,D/accuweather( 1779): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,D/accuweather( 1779): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,I/SurfaceFlinger(  256): id=12 createSurf (1080x1920),1 flag=404, NainActivit
,D/StatusBarManagerService(  757): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SamsungIME( 1719): getNextShiftState() cursorCapsMode : 0
,D/StatusBarManagerService(  757): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/OpenGLRenderer( 6276): Initialized EGL, version 1.4
,D/PointerIcon(  757): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  757): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  757): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  757): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6276): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6276): Enabling debug mode 0
,D/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25133208k
,D/ConnectivityService(  757): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3254): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1448709367656
,D/InputMethodManagerService(  757): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PowerManagerService(  757): [PWL] sb release: PowerManagerService.Broadcasts
,W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  757): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  757): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline(  757): Timeline: Activity_windows_visible id: ActivityRecord{196de92c u0 com.example.hello/.MainActivity t2} time:79966
,W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  757): SIOP:: AP = 330, PST = 381, CUR = 450
,I/SamsungIME( 1719): getCurrentCandidateView
,I/Timeline( 6276): Timeline: Activity_idle id: android.os.BinderProxy@19515472 time:79979
I/Timeline( 6276): Timeline: Activity_idle id: android.os.BinderProxy@19515472 time:79979
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 3254): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3254): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3254): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3254): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 11/28/2015 06:15 PM
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 11/28/2015 12:16 PM
D/daemonapp( 3254): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3254): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/AndroidProtocolHandler( 6276): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 6276): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1719): Dismiss ExpandCandiate
,D/JsMessageQueue( 6276): Set native->JS mode to OnlineEventsBridgeMode
,E/SQLiteLog( 1572): (10) POSIX Error : 11 SQLite Error : 3850
,I/SamsungIME( 1719): getDebugLevel  : 0x4f4c
,I/chromium( 6276): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6276): 
,I/SamsungIME( 1719): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1719): KeybaordView init() : load resources
,D/jxcore_app_log( 6276): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358315264
,D/JX-Cordova( 6276): jxcore cordova android initializing
,I/SamsungIME( 1719): getCurrentKeyboard
I/SamsungIME( 1719): getTextKeyboard
,D/SamsungIME( 1719): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 6276): Initializing JXcore engine
,W/jxcore-log( 6276): JXcore engine is ready
,D/CustomFrequencyManagerService(  757): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  tag : ACTIVITY_RESUME_BOOSTER@11
,W/jxcore-log( 6276): Starting JXcore engine
,E/auditd  ( 1863): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  757): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  757): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6363): MountEmulatedStorage()
E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD checking this for 1000
I/libpersona( 6363): KNOX_SDCARD not a persona
,E/SMD     (  297): DCD ON
,I/ActivityManager(  757): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6363 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/art     (  327): Explicit concurrent mark sweep GC freed 8815(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 13.513ms
,I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 10.570ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 277us total 9.778ms
,D/TimaKeyStoreProvider( 6363): TimaSignature is unavailable
,D/ActivityThread( 6363): Added TimaKeyStore provider
,D/ResourcesManager( 6363): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6363):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6363):  SeDenialReceiver : File path = null
,I/ActivityManager(  757): Killing 5240:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,W/jxcore-log( 6276): Platform android
W/jxcore-log( 6276): 
W/jxcore-log( 6276): Process ARCH arm
W/jxcore-log( 6276): 
E/lowmemorykiller(  253): Error writing /proc/5240/oom_score_adj; errno=22
,I/jxcore-log( 6276): JXcore Cordova bridge is ready!
I/jxcore-log( 6276): 
,W/jxcore-log( 6276): JXcore engine is started
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/jxcore-log( 6276): >> samsung-SM-N9005
E/jxcore-log( 6276): 
,I/jxcore-log( 6276): Total memory 2971471872
I/jxcore-log( 6276): 
,I/jxcore-log( 6276): Free memory 433950720
I/jxcore-log( 6276): 
I/jxcore-log( 6276): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6276): 
I/jxcore-log( 6276): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6276): 
,I/jxcore-log( 6276): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6276): 
,I/jxcore-log( 6276): Size 1080 1920
I/jxcore-log( 6276): 
,I/jxcore-log( 6276): Screen Brightness 162
I/jxcore-log( 6276): 
,E/jxcore-log( 6276): Dummy Error Log.
E/jxcore-log( 6276): 
,D/SamsungIME( 1719): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SSRM:a  (  757): DeviceInfo:: 000000100000
D/SSRM:a  (  757): SettingsAirViewInfo:: 010100000
,W/ProcessCpuTracker(  757): Skipping unknown process pid 6312
,W/ProcessCpuTracker(  757): Skipping unknown process pid 6313
W/ProcessCpuTracker(  757): Skipping unknown process pid 6319
W/ProcessCpuTracker(  757): Skipping unknown process pid 6334
W/ProcessCpuTracker(  757): Skipping unknown process pid 6378
,D/PowerManagerService(  757): [input device light] handleInputDeviceLightOff
,D/lights  (  757): button : 0 +
,D/lights  (  757): button : 0 -
,I/jxcore-log( 6276): getBuffer is called!!!!
I/jxcore-log( 6276): 
,W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  297): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  757): waitForAlarm result :4
,D/Finsky  ( 5445): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5445): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BluetoothAdapter( 6276): disable()
,E/BluetoothManagerService(  757): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6276): packageName : com.example.hello
,D/SecContentProvider(  757): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  757): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  757): mCursor = null
,D/WifiService(  757): setWifiEnabled: false pid=6276, uid=10256
,D/SettingsProvider(  757): name = wifi_on
,I/jxcore-log( 6276): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 6276): 
,I/jxcore-log( 6276): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6276): 
,D/AndroidRuntime( 6405): 
D/AndroidRuntime( 6405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6405): CheckJNI is OFF
,D/AndroidRuntime( 6405): readGMSProperty: start
,D/AndroidRuntime( 6405): readGMSProperty: already setted!!
,D/AndroidRuntime( 6405): readGMSProperty: end
,D/AndroidRuntime( 6405): addProductProperty: start
,E/AffinityControl( 6405): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6405): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService(  757): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  757): START PACKAGE DELETE: observer{895208872}
D/PackageManager(  757): pkg{<packageName>}
D/PackageManager(  757): user{0}
D/PackageManager(  757): caller{2000}
D/PackageManager(  757): flags{3}
D/PersonaManagerService(  757): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  757): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  757): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  757): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  757): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  757): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  757): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  757): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  757): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  757): !@killApplicatoin: 10256, uninstall pkg
,I/ActivityManager(  757): Force stopping com.example.hello appid=10256 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 6276:com.example.hello/u0a256 (adj 0): stop com.example.hello
,W/PackageSettings(  757): Skipping PackageSetting{2c239656 com.test.thalitest/10258} due to missing metadata
,I/WindowState(  757): WIN DEATH: Window{144c718d u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
,D/PointerIcon(  757): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  757): setMouseCustomIcon IconType is same.101
D/PointerIcon(  757): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  757): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  757): Force removing ActivityRecord{196de92c u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  757): Set to : 0
,D/CustomFrequencyManagerService(  757): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  757): mDVFSHelper.acquire()
,V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  757): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  757): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/ActivityManager(  757): Display changed displayId=0
,D/SurfaceWidgetView( 1440): destroyHardwareResources():993080641
,D/Launcher( 1440): onRestart, Launcher: 368430396
,W/ActivityManager(  757): Spurious death for ProcessRecord{28aff0c1 6276:com.example.hello/u0a256}, curProc for 6276: null
,I/ActivityManager(  757): Force stopping com.example.hello appid=10256 user=0: pkg removed
,E/SMD     (  297): DCD ON
,I/art     ( 6106): Explicit concurrent mark sweep GC freed 8275(486KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 424us total 25.003ms
,D/Launcher( 1440): onStart, Launcher: 368430396
D/Launcher.HomeView( 1440): onStart
,D/Launcher( 1440): onResume, Launcher: 368430396
W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SettingsProvider(  757): name = kids_home_mode
D/SettingsProvider(  757): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  757): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  757): selectionArgs: false
D/SettingsProvider(  757): selectionArgs: 10010
D/SecContentProvider(  757): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  757): ret = -1
D/Launcher.HomeView( 1440): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1779): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1779): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1779): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1779): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
,D/accuweather( 1779): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
D/ConnectivityService(  757): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher( 1440): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1440): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1779): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,E/SamsungIME( 1719): mOCRHelper is null
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/accuweather( 1779): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/accuweather( 1779): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
,D/accuweather( 1779): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1779): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1779): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1779): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1779): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,I/art     ( 4049): Explicit concurrent mark sweep GC freed 36921(2011KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 2.065ms total 42.112ms
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,W/GeofencerStateMachine( 1479): Ignoring removeGeofence because network location is disabled.
,I/art     ( 6050): Explicit concurrent mark sweep GC freed 3756(195KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 565us total 60.632ms
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  ( 6432): MountEmulatedStorage()
E/Zygote  ( 6432): v2
I/libpersona( 6432): KNOX_SDCARD checking this for 10023
I/libpersona( 6432): KNOX_SDCARD not a persona
,I/ActivityManager(  757): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6432 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/accuweather( 1779): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SELinux ( 6432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/MenuAppsGridFragment( 1440): onResume
,D/comsamsunglog( 1779): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1779): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
,D/comsamsunglog( 1779): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1779): [Accuweather J]>>> ==============================================================================================
I/SELinux ( 6432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WallpaperManager( 1440): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1440): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 1779): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,D/accuweather( 1779): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/EnterpriseDeviceManagerService(  757): Package has changed for user 0
D/EnterpriseDeviceManagerService(  757): Admin package name: com.google.android.gms
,I/art     (  757): Explicit concurrent mark sweep GC freed 41900(2MB) AllocSpace objects, 19(304KB) LOS objects, 17% free, 37MB/45MB, paused 1.843ms total 124.886ms
,I/art     (  757): WaitForGcToComplete blocked for 111.505ms for cause Explicit
,D/ResourcesManager(  757): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1779): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/accuweather( 1779): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1779): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1779): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Sat, 28 November
,D/ActivityManager(  757): handle home activity for 0
I/WallpaperManagerService(  757): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  757): post home show event for user 0
D/ActivityManager(  757): post active user change for 0
D/KnoxTimeoutHandler(  757): postActiveUserChange for user 0
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/accuweather( 1779): [Accuweather J]>>> SM:2087 [0:0] makeTimeText[1] time :Sat, 28 November 12:15 , new :Sat, 28 November 12:16 
,D/accuweather( 1779): [Accuweather J]>>> SM:2208 [0:0] uCCV : msg = -1, oT = true
,I/SurfaceFlinger(  256): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  757): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6432): TimaSignature is unavailable
,D/ActivityThread( 6432): Added TimaKeyStore provider
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/PointerIcon(  757): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  757): setMouseCustomIcon IconType is same.101
D/PointerIcon(  757): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  757): setHoveringSpenCustomIcon IconType is same.1
,D/accuweather( 1779): [Accuweather J]>>> SM:2171 [0:0] uCCV : time = 12:16
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager( 6432): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager( 1440): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,W/ResourcesManager( 1440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1440): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1440): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  757): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  757): mCursor = null
,W/ResourcesManager( 1440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1440): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/SurfaceWidget.Renderer( 1779): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1779): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ResourcesManager( 1440): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1440): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Launcher( 1440): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1440): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  757): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 6276 uid 10256
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MicrophoneInputStream( 1628): mic_starting gfk@37548f95
,V/AudioPolicyManager(  305): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  305): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  305): adev_open_input_stream: enter
E/audio_hw_primary(  305): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  305): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  305): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  305): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  305): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  305): adev_open_input_stream: exit
,I/AudioFlinger(  305): AudioFlinger's thread 0xb046c000 ready to run
V/audio_hw_primary(  305): in_standby: enter
V/audio_hw_primary(  305): in_standby: exit:  status(0)
,D/RegisteredServicesCache( 1417): empty dynamic service
,V/audio_hw_primary(  305): in_standby: enter
V/audio_hw_primary(  305): in_standby: exit:  status(0)
I/EDMNativeHelperService(  757): isMicrophoneEnabled
,I/HotwordRecognitionRnr( 1628): Starting hotword detection.
,V/AudioPolicyManager(  305): startInput() input 14
V/AudioPolicyManager(  305): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  305): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  305): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  305): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
I/KLMS-2.4.511: ( 6432): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/audio_hw_primary(  305): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  305): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  305): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  305): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1628): mic_started gfk@37548f95
,I/KLMS-2.4.511: ( 6432): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448709374371
,D/WallpaperManager( 1440): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1440): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,V/msm8974_platform(  305): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  305): start_input_stream: enter: usecase(7)
V/voice   (  305): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  305): start_input_stream: usecase(7)
D/PreProcess(  305): new SamsungRecord
D/PreProcess(  305): new NS
I/samsungRecord(  305): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  305): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  305): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  305): 1
D/SamsungRecord_NS(  305): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  305): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  305): select_devices: ENTER
V/audio_hw_primary(  305): select_devices: usecase(normal)
V/audio_hw_primary(  305): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  305): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  305): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  305): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  305): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  305): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  305): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  305): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  305): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  305): ACDB -> send_adm_topology
D/ACDB-LOADER(  305): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  305): ACDB -> send_asm_topology
D/ACDB-LOADER(  305): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  305): ACDB -> send_audtable
D/ACDB-LOADER(  305): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  305): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  305): ACDB -> send_audvoltable
D/ACDB-LOADER(  305): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  305): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  305): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  305): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  305): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  305): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: ADC1 Volume
D/audio_route(  305): Setting mixer control: value: 19
,D/StatusBarManagerService(  757): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  305): Setting mixer control: DEC6 Volume
D/audio_route(  305): Setting mixer control: value: 84
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/audio_route(  305): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  305): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  305): Setting mixer control: value: 1
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/audio_route(  305): Setting mixer control: DEC6 MUX, value: 2
,I/KLMS-2.4.511: ( 6432): MainReciver(): PACKAGE_REMOVED
,D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  305): enable_audio_route: apply mixer path: audio-record
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  305): Setting mixer control: value: 1
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): enable_audio_route: exit
V/audio_hw_primary(  305): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  305): start_input_stream: exit
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/KLMS-2.4.511: ( 6432): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,I/Timeline( 1440): Timeline: Activity_idle id: android.os.BinderProxy@368ea05a time:86676
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/HotwordWorker( 1628): onReady
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/RCPManagerService(  757): PackageReceiver onReceive()
I/HarmonyEASService(  757): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  757): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  757): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  757): uID is 10256
,V/EnterpriseBillingPolicy(  757): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  757): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  757): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  757): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  757): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  757): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  757): getBillingProfileForVpnEngine - end - null
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,E/Zygote  ( 6457): MountEmulatedStorage()
I/libpersona( 6457): KNOX_SDCARD checking this for 10116
E/Zygote  ( 6457): v2
I/libpersona( 6457): KNOX_SDCARD not a persona
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  757): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6457 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 5050:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/WallpaperManagerService(  757):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  757): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  757): handleActiveUserChange for user 0
,D/TaskPersister(  757): removeObsoleteFile: deleting file=2_task.xml
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/SELinux ( 6457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6457): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  757): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  757): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  757): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/TimaKeyStoreProvider( 6457): TimaSignature is unavailable
D/ActivityThread( 6457): Added TimaKeyStore provider
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,D/ResourcesManager( 6457): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/ResourcesManager(  757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14491( 6457): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager(  757): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491( 6457): ELMEngine.ELMEngine( context ).
,I/art     (  757): Explicit concurrent mark sweep GC freed 13743(827KB) AllocSpace objects, 3(48KB) LOS objects, 17% free, 37MB/45MB, paused 2.855ms total 379.287ms
,D/elm:14491( 6457): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  757): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/elm:14491( 6457): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 6457): ElmAgentService : onCreate()
,D/elm:14491( 6457): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6457): MainReceiver.listeningToPackageRemoved()
,D/elm:14491( 6457): MDMBridge.getInstance()
D/elm:14491( 6457): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6457): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6474): MountEmulatedStorage()
I/libpersona( 6474): KNOX_SDCARD checking this for 10021
E/Zygote  ( 6474): v2
I/libpersona( 6474): KNOX_SDCARD not a persona
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/ActivityManager(  757): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6474 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Timeline(  757): Timeline: Activity_windows_visible id: ActivityRecord{1104f4d3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:86928
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/PackageManager(  757): delete codoeFile: 
W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/AASAUninstall(  757):  com.example.hello not target!
D/PackageManager(  757): result of delete: 1{895208872}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,I/SELinux ( 6474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  757): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/SELinux ( 6474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/elm:14491( 6457): ElmAgentService : onDestroy().
E/SELinux ( 6474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  757): Killing 4370:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,W/Resources(  757): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  757): clearDefaults: com.example.hello
,I/CrashAnrDetector(  757): onPackageRemoved : com.example.hello
,D/AndroidRuntime( 6405): Shutting down VM
,D/TimaKeyStoreProvider( 6474): TimaSignature is unavailable
,D/ActivityThread( 6474): Added TimaKeyStore provider
,D/ResourcesManager( 6474): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6474): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6474): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6474): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 5777): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5777): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5777): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6491): MountEmulatedStorage()
,E/Zygote  ( 6491): v2
I/libpersona( 6491): KNOX_SDCARD checking this for 10043
I/libpersona( 6491): KNOX_SDCARD not a persona
,I/ActivityManager(  757): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6491 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 5083:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/SELinux ( 6491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6491): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  757): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 757  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 6491): TimaSignature is unavailable
,D/ActivityThread( 6491): Added TimaKeyStore provider
,D/ResourcesManager( 6491): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6491): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6491): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6491): PushLog.txt file is not deleted.
D/SPPClientService( 6491): PushLog.txt file is not deleted.
D/SPPClientService( 6491): ============PushLog. stop!
,I/SA      ( 5892): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5892): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10256 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  757): Killing 5330:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6510): MountEmulatedStorage()
E/Zygote  ( 6510): v2
I/libpersona( 6510): KNOX_SDCARD checking this for 10024
I/libpersona( 6510): KNOX_SDCARD not a persona
,I/ActivityManager(  757): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=6510 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 6510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6510): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/Mms/FreeMessageReceiver( 4798): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  757): enable value -1
I/TactileAssist(  757): internal enable value -1
I/TactileAssist(  757): intensity value -1
I/TactileAssist(  757): saveAppList value true
,I/TactileAssist(  757): List of disabled apps :
,D/TimaKeyStoreProvider( 6510): TimaSignature is unavailable
,D/ActivityThread( 6510): Added TimaKeyStore provider
,D/SettingsProvider(  757): name = reading_mode_app_list
,D/Mms/FreeMessageReceiverService( 4798): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4798): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/Compatibility( 5915): onReceive() it will make start service
,D/ResourcesManager( 6510): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/Compatibility( 5915): onHandleIntent()
,D/Compatibility( 5915): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10256, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5915): found: 2
D/Compatibility( 5915): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5915): skipping ResolveInfo{2233b32f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,D/Compatibility( 5915): considering ResolveInfo{15f5cd3c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5915): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5915): enabling receiver ResolveInfo{3698dac5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5915): enabling receiver ResolveInfo{b1b5c1a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 1628): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5915): enabling receiver ResolveInfo{26d2534b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/EventHub(  757): Removing device '/dev/input/event6' due to inotify event
,D/Compatibility( 5915): enabling receiver ResolveInfo{13f08128 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/RCPManager( 5350):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService(  757):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  757): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5068): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5068): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5068): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5068): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5068): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5068): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5068): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5068): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5068): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5068): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5068): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5068): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5068): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5068): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5068): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 5915): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5915): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5915): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/SQLiteLog( 6510): (28) failed to open "/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6510): (28) failed to open "/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6510): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6510): (14) os_unix.c:32503: (2) open(/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db) - 
,E/SQLiteDatabase( 6510): Failed to open database '/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db'.
E/SQLiteDatabase( 6510): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6510): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6510): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6510): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6510): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1864)
E/SQLiteDatabase( 6510): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/SQLiteDatabase( 6510): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5557)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/SQLiteDatabase( 6510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6510): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6510): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6510): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6510): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/AndroidRuntime( 6510): Shutting down VM
,I/EventHub(  757): Removing device '/dev/input/event7' due to inotify event
E/AndroidRuntime( 6510): FATAL EXCEPTION: main
E/AndroidRuntime( 6510): Process: com.sec.android.provider.logsprovider, PID: 6510
E/AndroidRuntime( 6510): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6510): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6510): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6510): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6510): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6510): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6510): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6510): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1864)
E/AndroidRuntime( 6510): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/AndroidRuntime( 6510): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/AndroidRuntime( 6510): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5557)
E/AndroidRuntime( 6510): 	... 11 more
,E/SQLiteLog( 1628): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1628): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1628): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04d24e1 in tid 6529 (IntentService[U)
,V/ApplicationPolicy(  757): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
,D/ResourcesManager(  757): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,E/AndroidRuntime(  757): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  757): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  757): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  757): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  757): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  757): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  757): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  757): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  757): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  757): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  757): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  757): 	... 5 more
,D/StatusBarManagerService(  757): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  757): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  757): setMouseCustomIcon IconType is same.101
D/PointerIcon(  757): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  757): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 6050): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,I/EventHub(  757): Removing device '/dev/input/event8' due to inotify event
,F/libc    (  757): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa97b0028 in tid 947 (ActivityManager)
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6535): MountEmulatedStorage()
E/Zygote  ( 6535): v2
I/libpersona( 6535): KNOX_SDCARD checking this for 10121
I/libpersona( 6535): KNOX_SDCARD not a persona
,I/ActivityManager(  757): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6535 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/EventHub(  757): Removing device '/dev/input/event9' due to inotify event
,I/DEBUG   (  293): failed to change ownership of /data/tombstones: Read-only file system
E/        (  293): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1628
,I/dumpstate( 6541): begin
,I/dumpstate( 6541): open lockfile failed Read-only file system
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6542 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6542): MountEmulatedStorage()
E/Zygote  ( 6542): v2
I/libpersona( 6542): KNOX_SDCARD checking this for 1000
I/libpersona( 6542): KNOX_SDCARD not a persona
,I/EventHub(  757): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 6535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/EventHub(  757): Removing device '/dev/input/event11' due to inotify event
,E/audit_log( 1863): File locking failed. error= Bad file number
,E/SELinux ( 6535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SELinux ( 6542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub(  757): Removing device '/dev/input/event12' due to inotify event
,I/DEBUG   (  293): failed to change ownership of /data/tombstones: Read-only file system
E/        (  293): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 757
,I/dumpstate( 6566): begin
I/dumpstate( 6566): open lockfile failed Read-only file system
,V/AudioPolicyManager(  305): stopInput() input 14
V/AudioPolicyManager(  305): releaseInput() 14
V/AudioPolicyManager(  305): closeInput(14)
,V/audio_hw_primary(  305): in_standby: enter
,I/Zygote  (  327): Process 1628 exited due to signal (7)
,E/audit_log( 1863): File locking failed. error= Bad file number
,V/audio_hw_primary(  305): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  305): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  305): disable_audio_route: reset mixer path: audio-record
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  305): Setting mixer control: value: 0
D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): disable_audio_route: exit
V/audio_hw_primary(  305): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: ADC1 Volume
D/audio_route(  305): Setting mixer control: value: 0
D/audio_route(  305): Setting mixer control: DEC6 Volume
D/audio_route(  305): Setting mixer control: value: 0
,D/audio_route(  305): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  305): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  305): Setting mixer control: value: 0
,D/audio_route(  305): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): stop_input_stream: exit: status(0)
V/audio_hw_primary(  305): in_standby: exit:  status(0)
V/audio_hw_primary(  305): adev_close_input_stream
V/audio_hw_primary(  305): in_standby: enter
V/audio_hw_primary(  305): in_standby: exit:  status(0)
E/audio_hw_primary(  305): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  305): releaseInput() exit
,E/installd(  308): eof
E/installd(  308): failed to read size
I/installd(  308): closing connection
,W/Sensors ( 1779): sensorservice died [0xaf0a2380]
,I/ServiceManager(  254): service 'phone_restriction_policy' died
I/ServiceManager(  254): service 'remoteinjection' died
I/ServiceManager(  254): service 'mum_container_policy' died
I/ServiceManager(  254): service 'enterprise_billing_policy' died
I/ServiceManager(  254): service 'knox_timakeystore_policy' died
I/ServiceManager(  254): service 'enterprise_policy' died
I/ServiceManager(  254): service 'statusbar' died
I/ServiceManager(  254): service 'clipboard' died
I/ServiceManager(  254): service 'clipboardEx' died
I/ServiceManager(  254): service 'network_management' died
I/ServiceManager(  254): service 'ABTPersistenceService' died
I/ServiceManager(  254): service 'textservices' died
I/ServiceManager(  254): service 'network_score' died
I/ServiceManager(  254): service 'netstats' died
I/ServiceManager(  254): service 'netpolicy' died
I/ServiceManager(  254): service 'usb' died
I/ServiceManager(  254): service 'serial' died
I/ServiceManager(  254): service 'uimode' died
I/ServiceManager(  254): service 'jobscheduler' died
I/ServiceManager(  254): service 'wifip2p' died
I/ServiceManager(  254): service 'wifi' died
I/ServiceManager(  254): service 'msapwifi' died
I/ServiceManager(  254): service 'wifiscanner' died
I/ServiceManager(  254): service 'rttmanager' died
I/ServiceManager(  254): service 'imms' died
I/ServiceManager(  254): service 'sec_analytics' died
I/ServiceManager(  254): service 'backup' died
I/ServiceManager(  254): service 'appwidget' died
I/ServiceManager(  254): service 'voiceinteraction' died
I/ServiceManager(  254): service 'SecExternalDisplayService' died
I/ServiceManager(  254): service 'diskstats' died
I/ServiceManager(  254): service 'mDNIe' died
I/ServiceManager(  254): service 'spengestureservice' died
I/ServiceManager(  254): service 'quickconnect' died
I/ServiceManager(  254): service 'samplingprofiler' died
I/ServiceManager(  254): service 'commontime_management' died
I/ServiceManager(  254): service 'dreams' died
I/ServiceManager(  254): service 'assetatlas' died
I/ServiceManager(  254): service 'print' died
I/ServiceManager(  254): service 'restrictions' died
I/ServiceManager(  254): service 'media_session' died
I/ServiceManager(  254): service 'media_router' died
I/ServiceManager(  254): service 'trust' died
I/ServiceManager(  254): service 'fingerprint' died
I/ServiceManager(  254): service 'launcherapps' died
I/ServiceManager(  254): service 'voip' died
I/ServiceManager(  254): service 'media_projection' died
I/ServiceManager(  254): service 'input_method' died
I/ServiceManager(  254): service 'accessibility' died
I/ServiceManager(  254): service 'hardware' died
I/ServiceManager(  254): service 'edmnativehelper' died
I/ServiceManager(  254): service 'activity' died
I/ServiceManager(  254): service 'cpuinfo' died
I/ServiceManager(  254): service 'permission' died
I/ServiceManager(  254): service 'context_aware' died
I/ServiceManager(  254): service 'scontext' died
I/ServiceManager(  254): service 'barbeam' died
I/ServiceManager(  254): service 'multiwindow_facade' died
I/ServiceManager(  254): service 'window' died
I/ServiceManager(  254): service 'input' died
I/ServiceManager(  254): service 'tactileassist' died
I/ServiceManager(  254): service 'bluetooth_manager' died
I/ServiceManager(  254): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  254): service 'rcp' died
I/ServiceManager(  254): service 'motion_recognition' died
I/ServiceManager(  254): service 'cover' died
I/ServiceManager(  254): service 'mount' died
I/ServiceManager(  254): service 'lock_settings' died
I/ServiceManager(  254): service 'device_policy' died
I/ServiceManager(  254): service 'harmony_eas_service' died
I/ServiceManager(  254): service 'sdp' died
I/ServiceManager(  254): service 'log_manager_service' died
I/ServiceManager(  254): service 'enterprise_license_policy' died
I/ServiceManager(  254): service 'application_policy' died
I/ServiceManager(  254): service 'wifi_policy' died
I/ServiceManager(  254): service 'schedulin,g_policy' died
I/ServiceManager(  254): service 'webviewupdate' died
I/ServiceManager(  254): service 'usagestats' died
I/ServiceManager(  254): service 'battery' died
I/ServiceManager(  254): service 'telephony.registry' died
I/ServiceManager(  254): service 'entropy' died
I/ServiceManager(  254): service 'sedenial' died
I/ServiceManager(  254): service 'vibrator' died
I/ServiceManager(  254): service 'tima' died
I/ServiceManager(  254): service 'cepproxyks' died
I/ServiceManager(  254): service 'CustomFrequencyManagerService' died
I/ServiceManager(  254): service 'samsung.smartfaceservice' died
I/ServiceManager(  254): service 'consumer_ir' died
I/ServiceManager(  254): service 'alarm' died
I/ServiceManager(  254): service 'connectivity' died
I/ServiceManager(  254): service 'sb_service' died
I/ServiceManager(  254): service 'servicediscovery' died
I/ServiceManager(  254): service 'updatelock' died
I/ServiceManager(  254): service 'notification' died
I/ServiceManager(  254): service 'devicestoragemonitor' died
I/ServiceManager(  254): service 'location' died
I/ServiceManager(  254): service 'country_detector' died
I/ServiceManager(  254): service 'search' died
I/ServiceManager(  254): service 'dropbox' died
I/ServiceManager(  254): service 'wallpaper' died
I/ServiceManager(  254): service 'audio' died
I/ServiceManager(  254): service 'DockObserver' died
I/ServiceManager(  254): service 'SEAMService' died
I/ServiceManager(  254): service 'persona' died
I/ServiceManager(  254): service 'account' died
I/ServiceManager(  254): service 'content' died
I/ServiceManager(  254): service 'DirEncryptService' died
I/ServiceManager(  254): service 'ReactiveService' died
I/ServiceManager(  254): service 'procstats' died
I/ServiceManager(  254): service 'gfxinfo' died
I/ServiceManager(  254): service 'dbinfo' died
I/ServiceManager(  254): service 'package' died
I/ServiceManager(  254): service 'meminfo' died
I/ServiceManager(  254): service 'user' died
I/ServiceManager(  254): service 'mdm.remotedesktop' died
I/ServiceManager(  254): service 'sensorservice' died
I/ServiceManager(  254): service 'batterystats' died
I/ServiceManager(  254): service 'appops' died
I/ServiceManager(  254): service 'power' died
I/ServiceManager(  254): service 'display' died
I/ServiceManager(  254): service 'persona_policy' died
W/Sensors ( 1479): sensorservice died [0xaf0c7340]
E/WifiManager( 1479): Channel connection lost
F/libc    ( 6542): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6542 (ndroid.keychain)
W/Sensors ( 1440): sensorservice died [0xaf09f340]
E/ActivityThread( 1652): Failed to find provider info for logs
W/AudioFlinger(  305): power manager service died !!!
W/AudioCache(  305): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
W/Sensors ( 1424): sensorservice died [0xaf09f240]
W/Sensors ( 1398): sensorservice died [0xaf09e9c0]
E/WifiManager( 1572): Channel connection lost
E/WifiManager( 1424): Channel connection lost
I/SurfaceFlinger(  256): id=13 Removed Mauncher (6/8)
I/SurfaceFlinger(  256): id=5 Removed TtatusBar (6/7)
I/SurfaceFlinger(  256): id=11 Removed Ieads Up (6/6)
I/SurfaceFlinger(  256): id=13 Removed Mauncher (-2/6)
I/SurfaceFlinger(  256): id=5 Removed TtatusBar (-2/6)
I/SurfaceFlinger(  256): id=6 Removed JmageWallpa (4/5)
I/SurfaceFlinger(  256): id=6 Removed JmageWallpa (-2/5)
I/SurfaceFlinger(  256): id=9 Removed EimLayer (2/4)
I/SurfaceFlinger(  256): id=10 Removed EimLayer (2/3)
I/SurfaceFlinger(  256): id=11 Removed Ieads Up (-2/3)
W/Sensors ( 4877): sensorservice died [0xaf0e2280]
W/Sensors ( 1186): sensorservice died [0xaf0a11c0]
E/WifiManager( 1306): Channel connection lost
I/SurfaceFlinger(  256): restart the boot-animation @ binderDied
I/SurfaceFlinger(  256): id=2 Removed GocusedStac (2/2)
I/SurfaceFlinger(  256): id=3 Removed EimLayer (0/1)
I/SurfaceFlinger(  256): id=4 Removed EimLayer (0/0)
I/SurfaceFlinger(  256): id=9 Removed EimLayer (-2/0)
I/SurfaceFlinger(  256): id=10 Removed EimLayer (-2/0)
I/SurfaceFlinger(  256): id=2 Removed GocusedStac (-2/0)
I/SurfaceFlinger(  256): id=3 Removed EimLayer (-2/0)
I/SurfaceFlinger(  256): id=4 Removed EimLayer (-2/0)
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb6962000
D/SurfaceFlinger(  256): Screen type=0 is already mode=2
E/WifiManager( 1186): Channel connection lost
F/libc    ( 6535): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6535 (.filterprovider)
E/AndroidRuntime( 1652): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1652): Process: android.process.acore, PID: 1652
E/AndroidRuntime( 1652): java.lang.IllegalArgumentException: Unknown URL content://logs/from_vvm
E/AndroidRuntime( 1652): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1652): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
E/AndroidRuntime( 1652): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1652): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/AndroidRuntime( 1652): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 1652): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 1652): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1652): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1652): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1652): Error reporting crash
E/AndroidRuntime( 1652): android.os.DeadObjectException
E/AndroidRuntime( 1652): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 1652): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 1652): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 1652): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 1652): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 1652): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 1652): Sending signal. PID: 1652 SIG: 9
E/ActivityThread( 6050): Failed to find provider info for com.samsung.android.provider.filterprovider
E/ActivityThread( 6050): Failed to find provider info for com.samsung.android.provider.filterprovider
E/AndroidRuntime( 6050): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 6050): Process: com.samsung.android.app.filterinstaller, PID: 6050
E/AndroidRuntime( 6050): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 6050): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 6050): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 6050): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 6050): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 6050): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6050): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6050): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6510): Error reporting crash
E/AndroidRuntime( 6510): android.os.DeadObjectException
E/AndroidRuntime( 6510): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6510): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6510): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6510): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6510): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6510): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6510): Sending signal. PID: 6510 SIG: 9
E/AndroidRuntime( 6050): Error reporting crash
E/AndroidRuntime( 6050): android.os.DeadObjectException
E/AndroidRuntime( 6050): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6050): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6050): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6050): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6050): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6050): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6050): Sending signal. PID: 6050 SIG: 9
W/Sensors ( 1887): sensorservice died [0xaf09ca40]
,I/DEBUG   (  293): failed to change ownership of /data/tombstones: Read-only file system
E/        (  293): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6542
,I/dumpstate( 6571): begin
,I/dumpstate( 6571): open lockfile failed Read-only file system
,E/audit_log( 1863): File locking failed. error= Bad file number
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0

```
