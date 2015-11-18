#### Test 50388019f4ce509_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
I/ServiceManager(  354): Waiting for service AtCmdFwd...
--------- beginning of system
V/AlarmManager(  903): waitForAlarm result :4
D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
D/LightsService(  903): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 903) 
D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
E/LightSensor(  903): Light old sensor_state 0, new sensor_state : 512 en : 1
I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
D/SensorManager(  903): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/SecContentProvider2(  903): uri = 14 selection = getSealedState
D/SecContentProvider2(  903): mCursor = null
D/BatteryService(  903): turn on LED for fully charged
D/ApplicationPolicy(  903): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  903): isApplicationStateBlocked userId -2 pkgname com.android.systemui
D/WindowManager(  903): showStatusBarByNotification() mOpenByNotification=false
I/AudioService(  903): getStreamVolume 1 index 0
D/NotificationService(  903): Noti Alert - doVibrate false convertStoV=true
V/Vibrator(  903): Called vibrateNotification() API - PUID: 1000, PackageName: android, type: 13
V/Vibrator(  903): Called vibrateImmVibe(int, MagnitudeType) API - PUID: 1000, PackageName: android
V/Vibrator(  903): vibrateImmVibe - PUID: 1000, PackageName: android, type: 13, mag: 0
D/VibratorService(  903): Turning vibrator off - ImmVibe.
D/PowerManagerService(  903): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1184
I/PowerManagerService(  903): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService(  903): Waking up from sleep (uid 10067)...
D/PowerManagerService(  903): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2d8043f1)
D/KeyguardViewMediator( 1184): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1184): notifyScreenOnLocked
D/Launcher( 1448): onRestart, Launcher: 733459063
D/PowerManagerService(  903): [s] UserActivityState : 0 -> 1
D/PowerManagerService(  903): [PWL] sb acquire: PowerManagerService.Display
I/DisplayPowerController(  903): Blocking screen on until initial contents have been drawn.
D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/SContextService(  903): 	.registerCallback : 1, client=
W/CAE     (  903): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
I/CAE     (  903): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  903): setCAProperty(ContextAwareService.java:469) - result : true
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/CAE     (  903): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  903): sendAttribute() : service = Auto Rotation
W/CAE     (  903): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/ActivityManager(  903): Display changed displayId=0
V/CAE     (  903): start(ContextProvider.java:126)
V/CAE     (  903): clear(AutoRotationRunner.java:182)
V/CAE     (  903): enable(AutoRotationRunner.java:158)
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/CAE     (  903): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  903): SendSensorHubData: send data = -79, 7, 0, 0
D/Sensorhubs(  306): sendContextData: -79, 7, 0, 0
D/CAE     (  903): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  903): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/KnoxNotification( 1184): ----- inflateViews : modified publicViewLocal -----
D/KnoxNotification( 1184): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1184): PersonaID is invalid or persona doesn't exists. : 0
D/CAE     (  903): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  903): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
D/CAE     (  903): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  903): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@310b1bc5, Service : AUTO_ROTATION(1)
W/CAE     (  903): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  903): addSContextService() : service = Auto Rotation
D/SContextService(  903): ===== SContext Service List =====
D/SContextService(  903): Listener : android.hardware.scontext.SContextService$Listener@38f091a, Service : Auto Rotation
D/SContextManager(  903):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@31b68bd6, service=Auto Rotation
D/AutomaticBrightnessController(  903): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  903): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  903): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/AutomaticBrightnessController(  903): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerManagerService(  903): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  903): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  903): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/QCOM PowerHAL(  903): Got set_interactive hint
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/AutomaticBrightnessController(  903): [api] [DAB] onSensorChanged : 1st lux : 57.7344
D/qdhwcomposer(  254): hwc_blank: Unblanking display: 0
D/AutomaticBrightnessController(  903): [DAB] updateAutoBrightnessSEC : 85(85.0)    5.0 < 57.7344 < 172.0 (0.0)
D/AutomaticBrightnessController(  903): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  903): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  903): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 2
I/AutomaticBrightnessController(  903): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 57
D/DisplayPowerController(  903): getFinalBrightness : 85 -> 85
D/DisplayPowerController(  903): animation target = 85, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/DisplayManagerService(  903): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  903): Display changed displayId=0
D/SensorManager(  903): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/PowerManagerService(  903): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 17ms
E/Sensors (  903): Acc old sensor_state 512, new sensor_state : 513 en : 1
D/InputManager-JNI(  903): setDeviceInteractive: 1
D/InputManager-JNI(  903): sysfs_write +: /sys/class/input/event4/device/enabled: 1
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/InputManager-JNI(  903): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/SensorManager(  903): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  903): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 15ms
D/InputManager-JNI(  903): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  903): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/NativeNfcManager( 1408): power state=4
D/SamsungIME( 1711): showDlgMsgBox : false true true
D/NfcService( 1408): call the applyRotuiing
D/PalmMotion(  903): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/PalmMotion(  903): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  903): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 903) 
D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/SSRM:a  (  903): DeviceInfo:: 000000100000
D/SSRM:a  (  903): SettingsAirViewInfo:: 010100000
V/UserPresentBroadcastReceiver( 1476): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/Launcher( 1448): onStart, Launcher: 733459063
D/Launcher.HomeView( 1448): onStart
D/Launcher( 1448): onResume, Launcher: 733459063
D/LightsService(  903): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 903) 
D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  903): turn off LED
D/LightsService(  903): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/SensorManager(  903): unregisterListener ::   
D/lights  (  903): led_pattern : 0 +
D/lights  (  903): led_pattern : 0 -
D/LightsService(  903): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SettingsProvider(  903): name = kids_home_mode
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/DisplayPowerController(  903): getFinalBrightness : 85 -> 85
D/SettingsProvider(  903): selectionArgs: 10010
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
D/DisplayPowerController(  903): animation target = 85, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Launcher.HomeView( 1448): onResume
D/KeyguardViewMediator( 1184): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 1184): onScreenTurnedOn()
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1780): [237392/8] Surface widget resume on instance = 1
D/accuweather( 1780): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1780): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1780): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1780): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
I/CAE     (  903): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     (  903): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  903): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  903): SendSensorHubData: send data = -76, 13, -47, 0
D/accuweather( 1780): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
D/Sensorhubs(  306): sendContextData: -76, 13, -47, 0
D/Launcher( 1448): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/Launcher( 1448): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/accuweather( 1780): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
D/accuweather( 1780): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1780): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1780): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
D/accuweather( 1780): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1780): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1780): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
D/accuweather( 1780): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
D/comsamsunglog( 1780): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1780): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1780): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1780): [Accuweather J]>>> ==============================================================================================
D/accuweather( 1780): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1780): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
D/accuweather( 1780): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Wed, 18 November
D/InputMethodManagerService(  903): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/accuweather( 1780): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/accuweather( 1780): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/accuweather( 1780): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
D/MenuAppsGridFragment( 1448): onResume
D/WallpaperManager( 1448): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1448): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/HotwordRecognitionRnr( 1647): Starting hotword detection.
I/MicrophoneInputStream( 1647): mic_starting gfk@3a8c5e63
D/MotionRecognitionService(  903):   mReceiver.onReceive : ACTION_SCREEN_ON
E/MotionRecognitionService(  903):  handler : SCREEN_ON end
D/GalleryCacheReady( 4894): Receive : home resume
I/WifiNative-HAL(  903): startHal
E/wifi    (  903): getStaticLongField sWifiHalHandle 0x9a9f280c
D/wifi    (  903): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x8020e6
I/WifiNative-HAL(  903): Could not start hal
V/AudioPolicyManager(  300): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  300): adev_open_input_stream: enter
E/audio_hw_primary(  300): adev_open_input_stream : jack_config 0
E/audio_hw_primary(  300): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_after_ns.pcm 
D/NotificationService(  903): ACTION_SCREEN_ON
E/audio_hw_primary(  300): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  300): adev_open_input_stream: exit
D/LightsService(  903): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 903) 
D/LightsService(  903): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/StatusBar.NetworkController( 1184): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1184): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=false enabledDesc:null
D/LightsService(  903): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  903): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/DisplayPowerController(  903): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  903): Unblocked screen on after 226 ms
D/DisplayPowerState(  903): !@ ColorFade exit
D/StatusBarKeyguardViewManager( 1184): callback.onShown()
D/InputManager-JNI(  903): sysfs_write -: /sys/class/input/event4/device/enabled: 1
I/AudioFlinger(  300): AudioFlinger's thread 0xb0456000 ready to run
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
I/EDMNativeHelperService(  903): isMicrophoneEnabled
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
D/ActivityManager(  903): handle home activity for 0
I/WallpaperManagerService(  903): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  903): post home show event for user 0
D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/Mms/UIEventReceiver( 4792): ui event
I/SurfaceFlinger(  254): id=8 Removed DolorFade (6/6)
I/SurfaceFlinger(  254): id=8 Removed DolorFade (-2/6)
E/libEGL  (  903): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  903): getFinalBrightness : 85 -> 85
D/DisplayPowerController(  903): animation target = 85, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  903): lcd : 85 +
D/lights  (  903): lcd : 85 -
D/DisplayPowerController(  903): getFinalBrightness : 85 -> 85
D/DisplayPowerController(  903): animation target = 85, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  903): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  903): SecHardwareInterface.setBatteryADC : true
V/AudioPolicyManager(  300): startInput() input 14
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  300): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  300): DeviceVector::refreshTypes() mDeviceTypes 80000004
D/PowerManagerService(  903): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  903): [input device light] handleInputDeviceLightOn
D/lights  (  903): button : 1 +
V/AudioPolicyManager(  300): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
V/audio_hw_primary(  300): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  300): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  300): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  300): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1647): mic_started gfk@3a8c5e63
D/WallpaperManagerService(  903):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  903): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
V/msm8974_platform(  300): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  300): start_input_stream: enter: usecase(7)
V/voice   (  300): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  300): start_input_stream: usecase(7)
D/PreProcess(  300): new SamsungRecord
D/PreProcess(  300): new NS
I/samsungRecord(  300): [samsungrecord] SamsungRecInit 
I/samsungRecord(  300): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  300): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  300): 1
D/SamsungRecord_NS(  300): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  300): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  300): select_devices: ENTER
V/audio_hw_primary(  300): select_devices: usecase(normal)
V/audio_hw_primary(  300): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  300): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  300): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  300): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  300): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  300): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  300): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  300): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  300): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  300): ACDB -> send_adm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_asm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_audtable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  300): ACDB -> send_audvoltable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  300): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  300): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  300): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: ADC1 Volume
D/audio_route(  300): Setting mixer control: value: 19
D/audio_route(  300): Setting mixer control: DEC6 Volume
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1448, uid=10010) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
D/audio_route(  300): Setting mixer control: value: 84
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 13
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 1
D/audio_route(  300): Setting mixer control: DEC6 MUX, value: 2
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): enable_audio_route: apply mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 1
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: exit
V/audio_hw_primary(  300): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
D/audio_hw_primary(  300): adev_set_parameters: enter: screen_state=on
V/audio_hw_primary(  300): start_input_stream: exit
V/voice   (  300): voice_set_parameters: enter: screen_state=on
V/voice   (  300): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  300): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  300): platform_set_parameters: exit with code(-2)
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/audio_hw_hfp(  300): audio_extn_hfp_set_parameters: enter
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
V/audio_hw_primary(  300): adev_set_parameters: exit
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/lights  (  903): button : 1 -
E/Zygote  ( 6232): MountEmulatedStorage()
E/Zygote  ( 6232): v2
I/libpersona( 6232): KNOX_SDCARD checking this for 10109
I/libpersona( 6232): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6232 uid=10109 gids={50109, 9997} abi=armeabi-v7a
I/SELinux ( 6232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SecExternalDisplayIntents_Java(  903): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
I/SELinux ( 6232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6232): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/art     (  324): Explicit concurrent mark sweep GC freed 8761(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 355us total 13.559ms
D/InputManager-JNI(  903): sysfs_write -: /sys/class/input/event2/device/enabled: 1
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 264us total 10.178ms
I/HotwordWorker( 1647): onReady
D/TimaKeyStoreProvider( 6232): TimaSignature is unavailable
D/ActivityThread( 6232): Added TimaKeyStore provider
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 10.590ms
E/qdexternal(  254): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 1
D/qdhwcomposer(  254): hwc_blank: Done unblanking display: 0
I/SurfaceFlinger(  254): id=9 createSurf (1080x750),1 flag=4, Ieads Up
D/SurfaceControl(  903): Excessive delay in setPowerMode(): 249ms
D/PowerManagerService(  903): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 251ms
D/IpRemoteDisplayController(  903): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  903): Bridge Server is not available
D/ResourcesManager( 6232): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
W/ResourcesManager( 6232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/BatteryMeterView( 1184): onDraw batteryColor : -1
I/Timeline( 1448): Timeline: Activity_idle id: android.os.BinderProxy@199d3c89 time:82204
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SystemUI/SystemUI.apk
W/ResourcesManager(  903): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
E/Zygote  ( 6250): MountEmulatedStorage()
I/libpersona( 6250): KNOX_SDCARD checking this for 10115
E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD not a persona
I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  903): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6250 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/GpsLocationProvider(  903): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PersonaManagerService(  903): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  903): MSG_ACTION_SCREEN_ON called
I/NfcService( 1408): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1408): call the applyRotuiing
D/accuweather( 1780): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
D/accuweather( 1780): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
D/ActivityThread( 6250): Added TimaKeyStore provider
I/SamsungIME( 1711): getNextShiftState() cursorCapsMode : 0
D/ResourcesManager( 6250): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
W/ResourcesManager( 6250): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6250): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
E/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
W/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25146308k
D/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
I/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 3332): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1447834369436
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PowerManagerService(  903): [PWL] sb release: PowerManagerService.Broadcasts
D/PushAndAttach( 6085): mAssignedMemoMap.size() :0
D/SSRM:n  (  903): SIOP:: AP = 320, PST = 373, CUR = 450
,V/TaskCloserActivity( 5612): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
I/ActivityManager(  903): Killing 5255:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 3332): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3332): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3332): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3332): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 11/18/2015 03:11 PM
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 11/18/2015 09:12 AM
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3332): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
I/ServiceManager(  354): Waiting for service AtCmdFwd...
D/Finsky  ( 5470): [905] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5470): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  903): Killing 5029:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
E/SQLiteLog( 1571): (10) POSIX Error : 11 SQLite Error : 3850
D/AndroidRuntime( 6267): 
D/AndroidRuntime( 6267): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6267): CheckJNI is OFF
D/AndroidRuntime( 6267): readGMSProperty: start
D/AndroidRuntime( 6267): readGMSProperty: already setted!!
D/AndroidRuntime( 6267): readGMSProperty: end
D/AndroidRuntime( 6267): addProductProperty: start
E/AffinityControl( 6267): AffinityControl: registerfunction enter
D/AndroidRuntime( 6267): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  903): inState():  stateMachine is null !!
I/PersonaManagerService(  903): PersonaId don't exist
I/ActivityManager(  903): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager(  903): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=11 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  903): Set to : 0
D/Launcher.HomeView( 1448): onPause
D/Launcher( 1448): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
I/SurfaceFlinger(  254): id=12 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 6267): Shutting down VM
V/TaskCloserActivity( 5612): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6293): MountEmulatedStorage()
E/Zygote  ( 6293): v2
I/libpersona( 6293): KNOX_SDCARD checking this for 10234
I/libpersona( 6293): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6293 uid=10234 gids={50234, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SELinux ( 6293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6293): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1448): updateVisibility : ActivityRecord{1c8afcf6 token=android.os.BinderProxy@199d3c89 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/MicrophoneInputStream( 1647): mic_close gfk@3a8c5e63
V/AudioPolicyManager(  300): stopInput() input 14
V/AudioPolicyManager(  300): releaseInput() 14
V/AudioPolicyManager(  300): closeInput(14)
I/HotwordRecognitionRnr( 1647): Stopping hotword detection.
I/HotwordRecognitionRnr( 1647): Hotword detection finished
V/audio_hw_primary(  300): in_standby: enter
D/TimaKeyStoreProvider( 6293): TimaSignature is unavailable
D/ActivityThread( 6293): Added TimaKeyStore provider
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  903): Display changed displayId=0
D/Launcher.HomeView( 1448): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1780): [237392/8] Surface widget pause on instance = 1
V/ActivityThread( 1448): updateVisibility : ActivityRecord{1c8afcf6 token=android.os.BinderProxy@199d3c89 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/accuweather( 1780): [Accuweather J]>>> SWW:212 [0:0] [SWW] onPause : rI = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1780): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1780): [Accuweather J]>>> SWW:222 [0:0] [SWW] onPause : size = 0
D/accuweather( 1780): [Accuweather J]>>> SWW:634 [0:0]  unRegisterTTReceiver !! 
V/audio_hw_primary(  300): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  300): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): disable_audio_route: reset mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): disable_audio_route: exit
V/audio_hw_primary(  300): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: ADC1 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC6 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  300): ------ audio_route_update_mixer ==============
D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/audio_hw_primary(  300): stop_input_stream: exit: status(0)
V/audio_hw_primary(  300): in_standby: exit:  status(0)
V/audio_hw_primary(  300): adev_close_input_stream
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
E/audio_hw_primary(  300): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  300): releaseInput() exit
D/SurfaceWidgetView( 1448): destroyHardwareResources():380049993
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 1780): [Accuweather J]>>> WCD:1431 [0:0] cARH()
D/accuweather( 1780): [Accuweather J]>>> WCD:549 [0:0]  onPause 
D/ResourcesManager( 6293): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/accuweather( 1780): [Accuweather J]>>> WR:475 [0:0] onPause : 1
D/accuweather( 1780): [Accuweather J]>>> SWW:540 [0:0] =================== , pause :1
D/Launcher( 1448): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1448): destroyHardwareResources():380049993
,I/WebViewFactory( 6293): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6293): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6293): Loading: webviewchromium
,I/LibraryLoader( 6293): Time to load native libraries: 5 ms (timestamps 3105-3110)
,I/LibraryLoader( 6293): Expected native library version number "",actual native library version number ""
,D/SSRM:a  (  903): DeviceInfo:: 000000100000
D/SSRM:a  (  903): SettingsAirViewInfo:: 010100000
,V/WebViewChromiumFactoryProvider( 6293): Binding Chromium to main looper Looper (main, tid 1) {d7edfaa}
,I/LibraryLoader( 6293): Expected native library version number "",actual native library version number ""
,I/chromium( 6293): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6293): Initializing chromium process, renderers=0
,W/art     ( 6293): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6293): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6293): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6293): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6293): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 6293): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6293): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6293): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6293): Local Branch: mybranch5813579
I/Adreno-EGL( 6293): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6293): Local Patches: NONE
I/Adreno-EGL( 6293): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/BluetoothAdapter( 6293): 245839771: getState() :  mService = null. Returning STATE_OFF
,E/SMD     (  293): DCD ON
,W/chromium( 6293): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6293): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6293): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6293): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6293): CordovaWebView is running on device made by: samsung
,W/art     ( 6293): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6293): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6293): performCreate Call secproduct feature valuefalse
D/Activity( 6293): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6293): Render dirty regions requested: true
,D/Atlas   ( 6293): Validating map...
,D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6293): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6293): HWUI protection enabled for context ,  &this =0xb3c189c0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6293): Enabling debug mode 0
,D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1711): getCurrentCandidateView
,I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +597ms
,I/SurfaceFlinger(  254): id=6 Removed Mauncher (4/10)
,I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/10)
,I/Timeline( 6293): Timeline: Activity_idle id: android.os.BinderProxy@2ee6875a time:83468
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1711): Dismiss ExpandCandiate
,I/chromium( 6293): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6293): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/PowerManagerService(  903): [input device light] handleInputDeviceLightOff
D/lights  (  903): button : 0 +
,D/JsMessageQueue( 6293): Set native->JS mode to OnlineEventsBridgeMode
,D/lights  (  903): button : 0 -
,I/chromium( 6293): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6293): 
,I/SamsungIME( 1711): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1711): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1711): KeybaordView init() : load resources
,I/SamsungIME( 1711): getCurrentKeyboard
I/SamsungIME( 1711): getTextKeyboard
,I/SurfaceFlinger(  254): id=12 Removed iello (7/9)
,I/SurfaceFlinger(  254): id=12 Removed iello (-2/9)
D/jxcore_app_log( 6293): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357818240
D/JX-Cordova( 6293): jxcore cordova android initializing
D/SamsungIME( 1711): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager(  903): mDVFSHelper.release()
I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{13c5b958 u0 com.example.hello/.MainActivity t2} time:83736
,W/jxcore-log( 6293): Initializing JXcore engine
W/jxcore-log( 6293): JXcore engine is ready
,W/jxcore-log( 6293): Starting JXcore engine
,E/auditd  ( 1853): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  903): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  903): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6352): MountEmulatedStorage()
E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD checking this for 1000
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6352 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6293): Platform android
W/jxcore-log( 6293): 
W/jxcore-log( 6293): Process ARCH arm
W/jxcore-log( 6293): 
,I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
,I/jxcore-log( 6293): JXcore Cordova bridge is ready!
I/jxcore-log( 6293): 
,W/jxcore-log( 6293): JXcore engine is started
,D/ResourcesManager( 6352): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6352):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6352):  SeDenialReceiver : File path = null
,I/ActivityManager(  903): Killing 4418:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@11
,E/jxcore-log( 6293): >> samsung-SM-N9005
E/jxcore-log( 6293): 
,I/jxcore-log( 6293): Total memory 2971471872
I/jxcore-log( 6293): 
,I/jxcore-log( 6293): Free memory 416661504
I/jxcore-log( 6293): 
I/jxcore-log( 6293): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6293): 
I/jxcore-log( 6293): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6293): 
,D/SamsungIME( 1711): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 6293): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6293): 
,I/jxcore-log( 6293): Size 1080 1920
I/jxcore-log( 6293): 
,I/jxcore-log( 6293): Screen Brightness 162
I/jxcore-log( 6293): 
,E/jxcore-log( 6293): Dummy Error Log.
E/jxcore-log( 6293): 
,I/jxcore-log( 6293): getBuffer is called!!!!
I/jxcore-log( 6293): 
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BluetoothAdapter( 6293): disable(),
,E/BluetoothManagerService(  903): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6293): packageName : com.example.hello
D/SecContentProvider(  903): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  903): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  903): mCursor = null
D/WifiService(  903): setWifiEnabled: false pid=6293, uid=10234
D/SettingsProvider(  903): name = wifi_on
I/jxcore-log( 6293): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 6293): 
I/jxcore-log( 6293): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6293): 
,E/SMD     (  293): DCD ON
,D/AndroidRuntime( 6385): 
D/AndroidRuntime( 6385): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6385): CheckJNI is OFF
,D/AndroidRuntime( 6385): readGMSProperty: start
D/AndroidRuntime( 6385): readGMSProperty: already setted!!
,D/AndroidRuntime( 6385): readGMSProperty: end
D/AndroidRuntime( 6385): addProductProperty: start
,E/AffinityControl( 6385): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6385): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  903): START PACKAGE DELETE: observer{348415433}
D/PackageManager(  903): pkg{<packageName>}
D/PackageManager(  903): user{0}
D/PackageManager(  903): caller{2000}
D/PackageManager(  903): flags{3}
,D/PersonaManagerService(  903): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  903): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  903): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  903): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  903): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  903): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  903): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  903): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  903): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  903): !@killApplicatoin: 10234, uninstall pkg
,I/ActivityManager(  903): Force stopping com.example.hello appid=10234 user=-1: uninstall pkg
I/ActivityManager(  903): Killing 6293:com.example.hello/u0a234 (adj 0): stop com.example.hello
,W/PackageSettings(  903): Skipping PackageSetting{20159141 com.test.thalitest/10224} due to missing metadata
,I/WindowState(  903): WIN DEATH: Window{157d9591 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  903): Force removing ActivityRecord{13c5b958 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  903): Set to : 0
,D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  903): mDVFSHelper.acquire()
,V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  903): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  903): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/SurfaceWidgetView( 1448): destroyHardwareResources():380049993
,I/ActivityManager(  903): Force stopping com.example.hello appid=10234 user=0: pkg removed
,D/Launcher( 1448): onRestart, Launcher: 733459063
,I/art     ( 6027): Explicit concurrent mark sweep GC freed 4536(229KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 334us total 18.618ms
,I/art     ( 6085): Explicit concurrent mark sweep GC freed 9199(527KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 16MB/21MB, paused 354us total 26.047ms
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 4856): Explicit concurrent mark sweep GC freed 36778(1979KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 15MB/26MB, paused 384us total 27.441ms
,E/SamsungIME( 1711): mOCRHelper is null
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/InputReader(  903): Reconfiguring input devices.  changes=0x00000010
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GeofencerStateMachine( 1476): Ignoring removeGeofence because network location is disabled.
,E/Zygote  ( 6411): MountEmulatedStorage()
,E/Zygote  ( 6411): v2
I/libpersona( 6411): KNOX_SDCARD checking this for 10023
I/libpersona( 6411): KNOX_SDCARD not a persona
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/ActivityManager(  903): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6411 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager(  903): Spurious death for ProcessRecord{3c4bafc 6293:com.example.hello/u0a234}, curProc for 6293: null
D/Launcher( 1448): onStart, Launcher: 733459063
D/Launcher.HomeView( 1448): onStart
,D/Launcher( 1448): onResume, Launcher: 733459063
,I/SELinux ( 6411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6411): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider(  903): name = kids_home_mode
D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 10010
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  903): ret = -1
D/Launcher.HomeView( 1448): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1780): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1780): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
,D/accuweather( 1780): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1780): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1780): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/EnterpriseDeviceManagerService(  903): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  903): Admin package name: com.google.android.gms
D/Launcher( 1448): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1448): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1780): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,D/accuweather( 1780): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1780): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
,D/accuweather( 1780): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
,D/accuweather( 1780): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1780): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1780): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
,D/accuweather( 1780): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,D/accuweather( 1780): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/MenuAppsGridFragment( 1448): onResume
,D/ActivityManager(  903): handle home activity for 0
I/WallpaperManagerService(  903): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  903): post home show event for user 0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1780): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
D/SurfaceWidget.Renderer( 1780): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1780): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/comsamsunglog( 1780): [Accuweather J]>>> ==============================================================================================
D/comsamsunglog( 1780): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
,D/comsamsunglog( 1780): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1780): [Accuweather J]>>> ==============================================================================================
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/accuweather( 1780): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1780): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1780): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Wed, 18 November
,D/TimaKeyStoreProvider( 6411): TimaSignature is unavailable
,D/accuweather( 1780): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/accuweather( 1780): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,D/ActivityThread( 6411): Added TimaKeyStore provider
,D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,I/art     (  903): Explicit concurrent mark sweep GC freed 41399(2MB) AllocSpace objects, 18(288KB) LOS objects, 17% free, 37MB/45MB, paused 4.414ms total 171.573ms
I/art     (  903): WaitForGcToComplete blocked for 168.635ms for cause Explicit
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/Launcher( 1448): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/Launcher( 1448): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 6411): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 6293 uid 10234
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  903): mCursor = null
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/RegisteredServicesCache( 1408): empty dynamic service
,I/MicrophoneInputStream( 1647): mic_starting gfk@15f665b7
,I/HotwordRecognitionRnr( 1647): Starting hotword detection.
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,V/AudioPolicyManager(  300): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  300): adev_open_input_stream: enter
E/audio_hw_primary(  300): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  300): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  300): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  300): adev_open_input_stream: exit
,I/AudioFlinger(  300): AudioFlinger's thread 0xb0563000 ready to run
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/EDMNativeHelperService(  903): isMicrophoneEnabled
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,V/AudioPolicyManager(  300): startInput() input 16
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  300): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  300): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  300): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
V/audio_hw_primary(  300): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  300): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  300): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  300): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1647): mic_started gfk@15f665b7
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/KLMS-2.4.511: ( 6411): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
V/msm8974_platform(  300): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  300): start_input_stream: enter: usecase(7)
V/voice   (  300): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  300): start_input_stream: usecase(7)
D/PreProcess(  300): new SamsungRecord
D/PreProcess(  300): new NS
I/samsungRecord(  300): [samsungrecord] SamsungRecInit 
I/samsungRecord(  300): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  300): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  300): 1
D/SamsungRecord_NS(  300): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  300): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  300): select_devices: ENTER
V/audio_hw_primary(  300): select_devices: usecase(normal)
V/audio_hw_primary(  300): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  300): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  300): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  300): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  300): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  300): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  300): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  300): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  300): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  300): ACDB -> send_adm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_asm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_audtable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  300): ACDB -> send_audvoltable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  300): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  300): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  300): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: ADC1 Volume
D/audio_route(  300): Setting mixer control: value: 19
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/audio_route(  300): Setting mixer control: DEC6 Volume
D/audio_route(  300): Setting mixer control: value: 84
I/KLMS-2.4.511: ( 6411): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1447834377250
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 13
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 1
I/KLMS-2.4.511: ( 6411): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6411): MainReciver(): REPLACING: false | pkgName: com.example.hello
D/audio_route(  300): Setting mixer control: DEC6 MUX, value: 2
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): enable_audio_route: apply mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 1
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: exit
V/audio_hw_primary(  300): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  300): start_input_stream: exit
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/WallpaperManager( 1448): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1448): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/HotwordWorker( 1647): onReady
,I/Timeline( 1448): Timeline: Activity_idle id: android.os.BinderProxy@199d3c89 time:90213
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  ( 6439): MountEmulatedStorage()
E/Zygote  ( 6439): v2
I/libpersona( 6439): KNOX_SDCARD checking this for 10116
I/libpersona( 6439): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6439 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  903): Killing 5094:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/SELinux ( 6439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/SELinux ( 6439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     (  903): Explicit concurrent mark sweep GC freed 7042(474KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 4.904ms total 238.107ms
,D/TimaKeyStoreProvider( 6439): TimaSignature is unavailable
,D/ActivityThread( 6439): Added TimaKeyStore provider
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 6439): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  903): mDVFSHelper.release()
D/CustomFrequencyManagerService(  903): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/RCPManagerService(  903): PackageReceiver onReceive()
,I/HarmonyEASService(  903): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  903): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  903): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  903): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  903): uID is 10234
,V/EnterpriseBillingPolicy(  903): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  903): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  903): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  903): getBillingProfileForVpnEngine - end - null
,D/elm:14491( 6439): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/PackageManager(  903): delete codoeFile: 
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/elm:14491( 6439): ELMEngine.ELMEngine( context ).
I/AASAUninstall(  903):  com.example.hello not target!
D/PackageManager(  903): result of delete: 1{348415433}
,D/elm:14491( 6439): MDMBridge.setEnterpriseBridge()
,D/AndroidRuntime( 6385): Shutting down VM
,D/WallpaperManagerService(  903):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  903): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
,D/TaskPersister(  903): removeObsoleteFile: deleting file=2_task.xml
,D/elm:14491( 6439): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 6439): ElmAgentService : onCreate()
,D/elm:14491( 6439): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14491( 6439): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6439): MDMBridge.getInstance()
D/elm:14491( 6439): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6439): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,E/Zygote  ( 6456): MountEmulatedStorage()
E/Zygote  ( 6456): v2
I/libpersona( 6456): KNOX_SDCARD checking this for 10021
I/libpersona( 6456): KNOX_SDCARD not a persona
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  903): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6456 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux ( 6456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/elm:14491( 6439): ElmAgentService : onDestroy().
,E/SELinux ( 6456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 5353:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/TimaKeyStoreProvider( 6456): TimaSignature is unavailable
,D/ActivityThread( 6456): Added TimaKeyStore provider
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager( 6456): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  903): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6456): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6456): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6456): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/PCWCLIENTTRACE_PushUtil( 5794): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5794): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5794): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5794): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{3977dc20 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:90493
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  903): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  903): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  903): clearDefaults: com.example.hello
,I/CrashAnrDetector(  903): onPackageRemoved : com.example.hello
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6472): MountEmulatedStorage()
E/Zygote  ( 6472): v2
I/libpersona( 6472): KNOX_SDCARD checking this for 10043
I/libpersona( 6472): KNOX_SDCARD not a persona
,I/SELinux ( 6472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  903): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6472 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6472): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 5376:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6472): TimaSignature is unavailable
,D/ActivityThread( 6472): Added TimaKeyStore provider
,D/CustomFrequencyManagerService(  903): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 903  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager( 6472): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 6472): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6472): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6472): PushLog.txt file is not deleted.
,D/SPPClientService( 6472): PushLog.txt file is not deleted.
D/SPPClientService( 6472): ============PushLog. stop!
,E/SQLiteLog( 6472): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6472): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6472): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6472): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6472): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6472): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6472): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6472): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6472): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/LNoti   ( 6472): [b] open fail. SQLException occured
I/SA      ( 5888): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 5888): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10234 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  903): Killing 5431:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
E/SharedPreferencesImpl( 4894): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/Mms/FreeMessageReceiver( 4792): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  903): enable value -1
I/TactileAssist(  903): internal enable value -1
I/TactileAssist(  903): intensity value -1
I/TactileAssist(  903): saveAppList value true
,I/TactileAssist(  903): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4792): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4792): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/SettingsProvider(  903): name = reading_mode_app_list
,I/EventHub(  903): Removing device '/dev/input/event6' due to inotify event
,I/EventHub(  903): Removing device '/dev/input/event7' due to inotify event
,D/Compatibility( 5930): onReceive() it will make start service
,D/Compatibility( 5930): onHandleIntent()
,D/Compatibility( 5930): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10234, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5930): found: 2
D/Compatibility( 5930): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5930): skipping ResolveInfo{36c34c76 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5930): considering ResolveInfo{2bb7b277 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5930): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5930): enabling receiver ResolveInfo{14a16ee4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5930): enabling receiver ResolveInfo{20dddf4d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 1647): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5930): enabling receiver ResolveInfo{1b0fba02 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5930): enabling receiver ResolveInfo{2feaff13 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl( 5044): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
E/SharedPreferencesImpl( 5930): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 5930): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5930): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 5044): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5044): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5044): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5044): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
E/SQLiteDatabase( 5044): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5044): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5044): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5044): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5044): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5044): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5044): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5044): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5044): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5044): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5044): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5044): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5044): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5044): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5044): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5044): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5044): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5044): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5044): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5044): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5044): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5044): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5044): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5044): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5044): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5044): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Zygote  ( 6494): MountEmulatedStorage()
E/Zygote  ( 6494): v2
I/libpersona( 6494): KNOX_SDCARD checking this for 1000
I/libpersona( 6494): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/EventHub(  903): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog( 1647): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 1647): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1647): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa04204e1 in tid 6492 (IntentService[U)
,I/SELinux ( 6494): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub(  903): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 6494): TimaSignature is unavailable
,D/ActivityThread( 6494): Added TimaKeyStore provider
,D/ResourcesManager( 6494): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6494): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 6494): Unable to create files subdir /data/data/com.sec.knox.bridge/cache
E/ActivityThread( 6494): Unable to setupGraphicsSupport due to missing cache directory
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1647
,I/EventHub(  903): Removing device '/dev/input/event10' due to inotify event
,I/dumpstate( 6509): begin
,W/        ( 6494): Zip: inflate read failed (11191 vs 32768)
I/dumpstate( 6509): open lockfile failed No such file or directory
E/dumpstate( 6509): Cannot get free space size. So, skip dumpstate.
,D/AndroidRuntime( 6494): Shutting down VM
,E/AndroidRuntime( 6494): FATAL EXCEPTION: main
E/AndroidRuntime( 6494): Process: com.sec.knox.bridge, PID: 6494
E/AndroidRuntime( 6494): java.lang.RuntimeException: Unable to instantiate receiver com.sec.knox.bridge.PersonaShortcutReceiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.knox.bridge.PersonaShortcutReceiver" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/app/Bridge/Bridge.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6494): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2972)
E/AndroidRuntime( 6494): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6494): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6494): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6494): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6494): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6494): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6494): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.knox.bridge.PersonaShortcutReceiver" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/app/Bridge/Bridge.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6494): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6494): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6494): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6494): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2967)
E/AndroidRuntime( 6494): 	... 9 more
E/AndroidRuntime( 6494): 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/app/Bridge/Bridge.apk': I/O Error
E/AndroidRuntime( 6494): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6494): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6494): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6494): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6494): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6494): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6494): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6494): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6494): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6494): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6494): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6494): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6494): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6494): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6494): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6494): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6494): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6494): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6494): 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6494): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6494),: 		... 7 more
E/AndroidRuntime( 6494): 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@app@Bridge@Bridge.apk@classes.dex': Read-only file system
E/AndroidRuntime( 6494): 		... 27 more
E/AndroidRuntime( 6494): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/Bridge/Bridge.apk'
E/AndroidRuntime( 6494): 		... 27 more
E/AndroidRuntime( 6494): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/Bridge/arm/Bridge.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6494): 		... 27 more
E/AndroidRuntime( 6494): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6494): 		... 27 more
E/AndroidRuntime( 6494): 	Suppressed: java.lang.ClassNotFoundException: com.sec.knox.bridge.PersonaShortcutReceiver
E/AndroidRuntime( 6494): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6494): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6494): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6494): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6494): 		... 11 more
E/AndroidRuntime( 6494): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.sec.knox.bridge
I/EventHub(  903): Removing device '/dev/input/event11' due to inotify event
E/AndroidRuntime(  903): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  903): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  903): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  903): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  903): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  903): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  903): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  903): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  903): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  903): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  903): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  903): 	... 5 more
D/ResourcesManager(  903): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(  903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
,E/audit_log( 1853): File locking failed. error= Bad file number
,W/ContextImpl( 6027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,F/libc    (  903): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa9766028 in tid 986 (ActivityManager)
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/EventHub(  903): Removing device '/dev/input/event12' due to inotify event
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,V/AudioPolicyManager(  300): stopInput() input 16
V/AudioPolicyManager(  300): releaseInput() 16
V/AudioPolicyManager(  300): closeInput(16)
,V/audio_hw_primary(  300): in_standby: enter
,E/Zygote  ( 6514): MountEmulatedStorage()
,E/Zygote  ( 6514): v2
I/libpersona( 6514): KNOX_SDCARD checking this for 1000
I/libpersona( 6514): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub(  903): Removing device '/dev/input/event13' due to inotify event
,V/audio_hw_primary(  300): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  300): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): disable_audio_route: reset mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 0
,D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): disable_audio_route: exit
V/audio_hw_primary(  300): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: ADC1 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC6 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC6 MUX, value: 0
,D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): stop_input_stream: exit: status(0)
V/audio_hw_primary(  300): in_standby: exit:  status(0)
V/audio_hw_primary(  300): adev_close_input_stream
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
E/audio_hw_primary(  300): adev_close_input_stream, set jack_in to null
,V/AudioPolicyManager(  300): releaseInput() exit
,I/Zygote  (  324): Process 1647 exited due to signal (7)
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 903
,I/SELinux ( 6514): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dumpstate( 6520): begin
,I/dumpstate( 6520): open lockfile failed No such file or directory
E/dumpstate( 6520): Cannot get free space size. So, skip dumpstate.
,E/libsuspend(  903): Error reading from /sys/power/wakeup_count: Interrupted system call
E/MotionRecognitionService(  903): Motion Thread--
,E/audit_log( 1853): File locking failed. error= Bad file number
,W/Sensors ( 4894): sensorservice died [0xaf138200]
,W/Sensors ( 1780): sensorservice died [0xaf118640]
,W/Sensors ( 1476): sensorservice died [0xaf1342c0]
,E/WifiManager( 1476): Channel connection lost
,I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'application_policy' died
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
I/ServiceManager(  252): service 'netpolicy' died
E/ActivityThread( 6027): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'connectivity' died
E/ActivityThread( 6027): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
I/ServiceManager(  252): service 'notification' died
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
E/AndroidRuntime( 6494): Error reporting crash
E/AndroidRuntime( 6494): android.os.DeadObjectException
E/AndroidRuntime( 6494): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6494): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6494): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6494): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6494): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6494): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/ServiceManager(  252): service 'assetatlas' died
I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
I/ServiceManager(  25,2): service 'media_router' died
I/Process ( 6494): Sending signal. PID: 6494 SIG: 9
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
I/ServiceManager(  252): service 'permission' died
E/AndroidRuntime( 6027): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 6027): Process: com.samsung.android.app.filterinstaller, PID: 6027
E/AndroidRuntime( 6027): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 6027): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 6027): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 6027): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 6027): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6027): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6027): Error reporting crash
E/AndroidRuntime( 6027): android.os.DeadObjectException
E/AndroidRuntime( 6027): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6027): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6027): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6027): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6027): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6027): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6027): Sending signal. PID: 6027 SIG: 9
F/libc    ( 6514): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c890 in tid 6514 (ndroid.keychain)
E/WifiManager( 1184): Channel connection lost
W/AudioFlinger(  300): power manager service died !!!
W/AudioCache(  300): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
W/Sensors ( 1448): sensorservice died [0xaf1f8280]
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
W/Sensors ( 1184): sensorservice died [0xaf1411c0]
E/WifiManager( 1421): Channel connection lost
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (4/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=11 Removed EimLayer (2/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (2/3)
I/SurfaceFlinger(  254): id=9 Removed Ieads Up (2/2)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/2)
I/SurfaceFlinger(  254): id=11 Removed EimLayer (-2/2)
I/SurfaceFlinger(  254): id=14 Removed Mauncher (1/1)
W/Sensors ( 1421): sensorservice died [0xaf1421c0]
W/Sensors ( 1895): sensorservice died [0xaf1a99c0]
W/Sensors ( 1395): sensorservice died [0xaf1a99c0]
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/0)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/0)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  254): id=9 Removed Ieads Up (-2/0)
I/SurfaceFlinger(  254): id=14 Removed Mauncher (-2/0)
E/WifiManager( 1305): Channel connection lost
E/WifiManager( 1571): Channel connection lost
,I/DEBUG   (  286): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  286): failed to open /data/tombstones: No such file or directory
E/        (  286): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6514
,I/dumpstate( 6539): begin
,I/dumpstate( 6539): open lockfile failed No such file or directory
E/dumpstate( 6539): Cannot get free space size. So, skip dumpstate.
,E/installd(  303): eof
E/installd(  303): failed to read size
I/installd(  303): closing connection
,E/audit_log( 1853): File locking failed. error= Bad file number
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0

```
