#### Test 50388019f4ce509_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
I/PowerManagerService( 1019): [PWL] Off : 15s ago
--------- beginning of main
E/lights  ( 1019): write_int failed to open -1
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1019): turn on LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId -1 pkgname com.android.systemui
I/ValidateNoPeople( 1019): skipping global notification
D/WindowManager( 1019): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1178
I/PowerManagerService( 1019): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1019): Waking up from sleep (uid 10049)...
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate( 1019): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2921904f)
D/PowerManagerService( 1019): [s] UserActivityState : 0 -> 1
D/KeyguardViewMediator( 1178): onScreenTurnedOn, seq = 2
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Display
D/KeyguardViewMediator( 1178): notifyScreenOnLocked
I/DisplayPowerController( 1019): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1019): sensor enabled
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1019): [SO] changed settle time [0]
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 255 -> 255
D/SensorService( 1019): [SO] setDelay [200000000]
D/DisplayPowerController( 1019): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorService( 1019): [SO] activate (ident=0xb909f298, enabled=1)
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 255 -> 255
D/SensorService( 1019): [SO] AR_init
D/DisplayPowerController( 1019): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/DisplayManagerService( 1019): !@display_state: OFF -> ON
D/Launcher( 1479): onRestart, Launcher: 815651836
I/libsuspend( 1019): !@autosuspend_wakeup_count_disable
I/libsuspend( 1019): !@autosuspend_wakeup_count_disable done
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb8665690
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 2 on display: 0
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
I/DisplayManagerService( 1019): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1019): Display changed displayId=0
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/ActivityManager( 1019): Display changed displayId=0
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/Launcher( 1479): onStart, Launcher: 815651836
D/Launcher.HomeView( 1479): onStart
D/KeyguardViewMediator( 1178): handleNotifyScreenOn
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1019) 
D/Launcher( 1479): onResume, Launcher: 815651836
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/SettingsProvider( 1019): name = kids_home_mode
D/BatteryService( 1019): turn off LED
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/StatusBarKeyguardViewManager( 1178): onScreenTurnedOn()
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
E/lights  ( 1019): write_led_info failed to open -1
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/lights  ( 1019): write_led_info failed to open -1
E/SmartFaceService( 1019): fail to set sysfs 1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
E/lights  ( 1019): write_led_info failed to open -1
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
D/Launcher.HomeView( 1479): onResume
D/SecKeyguardClockSingleView( 1178): onScreenTurnedOn
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/PalmMotion( 1019): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1019): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1019): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1019): [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
E/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
D/SamsungIME( 1765): showDlgMsgBox : false true true
D/NfcService( 1436): call the applyRouting
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
D/MenuAppsGridFragment( 1479): onResume
D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/InputMethodManagerService( 1019): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_ON
E/MotionRecognitionService( 1019):  handler : SCREEN_ON end
,I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9ebb87fc
I/WifiNative-HAL( 1019): Could not start hal
D/NotificationService( 1019): ACTION_SCREEN_ON
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
V/UserPresentBroadcastReceiver( 1641): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : -1
I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@14de6341 time:66166
D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/KeyguardServiceDelegate( 1019): **** SHOWN CALLED ****
D/StatusBarKeyguardViewManager( 1178): callback.onShown()
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/DisplayPowerController( 1019): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
I/DisplayPowerController( 1019): Unblocked screen on after 180 ms
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
D/DisplayPowerState( 1019): !@ ColorFade exit
I/SurfaceFlinger(  257): id=10 Removed DolorFade (8/8)
I/SurfaceFlinger(  257): id=10 Removed DolorFade (-2/8)
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 255 -> 255
E/libEGL  ( 1019): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1019): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1019): lcd : 255 +
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 255 -> 255
D/lights  ( 1019): lcd : 255 -
D/DisplayPowerController( 1019): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1019): SecHardwareInterface.setBatteryADC : true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/BatteryMeterView( 1178): onDraw batteryColor : -1
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/SensorService( 1019): [SO] currT = 66201435000, prevT = 50031029000, diff = 16170406000, [-0.345 0.019 9.883]
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/GalleryCacheReady( 4229): Receive : home resume
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/Recents_RecreateReceiver( 2341): onReceive by home
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
V/TaskCloserActivity( 4743): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
D/Mms/UIEventReceiver( 4083): ui event
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 2 on display 0
D/SurfaceControl( 1019): Excessive delay in setPowerMode(): 229ms
D/PowerManagerService( 1019): Excessive delay in !@display_state: ON: 230ms
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1019): Bridge Server is not available
D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_ON
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/Zygote  ( 5063): MountEmulatedStorage()
E/Zygote  ( 5063): v2
I/libpersona( 5063): KNOX_SDCARD checking this for 10135
I/libpersona( 5063): KNOX_SDCARD not a persona
I/SELinux ( 5063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5063 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 5063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/PersonaManagerService( 1019): ACTION_SCREEN_ON onReceive
D/TimaKeyStoreProvider( 5063): TimaSignature is unavailable
D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_ON called
D/ActivityThread( 5063): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1436): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1436): call the applyRouting
W/ResourcesManager( 5063): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
D/accuweather( 1687): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1687): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1687): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1687): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1687): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1687): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1687): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1687): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
D/accuweather( 1687): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1687): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
E/accuweather( 1687): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 09 12
I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1019): Killing 4478:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1019): Excessive delay in MISC setInteractive(true) while turning screen on: 160ms
I/QCOM PowerHAL( 1019): Got set_interactive hint
D/PowerManagerService( 1019): Excessive delay in nativeSetInteractive(true): 161ms
D/PowerManagerService( 1019): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 392ms
D/lights  ( 1019): button : 1 +
D/SensorService( 1019): [SO] currT = 66401276000, prevT = 50031029000, diff = 16370247000, [-0.345 0.038 9.864]
D/SensorService( 1019): [SO] -0.345 0.038 9.864
D/SensorService( 1019): [SO] [100 -> 255]
I/SamsungIME( 1765): getNextShiftState() cursorCapsMode : 0
D/AndroidRuntime( 5057): 
D/AndroidRuntime( 5057): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5057): CheckJNI is OFF
D/AndroidRuntime( 5057): readGMSProperty: start
D/AndroidRuntime( 5057): readGMSProperty: already setted!!
D/AndroidRuntime( 5057): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5057): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5057): readGMSProperty: end
D/AndroidRuntime( 5057): addProductProperty: start
D/lights  ( 1019): button : 1 -
D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Broadcasts
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4478/cgroup.procs: No such file or directory
D/SSRM:n  ( 1019): SIOP:: AP = 330
D/daemonapp( 1731): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1731): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1731): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1731): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1731): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1731): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1447855860000
D/daemonapp( 1731): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1447834351030
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1731): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1731): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1731): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1731): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1731): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1731): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
E/AffinityControl( 5057): AffinityControl: registerfunction enter
D/AndroidRuntime( 5057): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1479
D/Launcher.HomeView( 1479): onPause
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 5057): Shutting down VM
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 4743): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
E/Zygote  ( 5089): MountEmulatedStorage()
E/Zygote  ( 5089): v2
I/libpersona( 5089): KNOX_SDCARD checking this for 10333
I/libpersona( 5089): KNOX_SDCARD not a persona
I/SELinux ( 5089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5089 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5089): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, iello
D/TimaKeyStoreProvider( 5089): TimaSignature is unavailable
D/ActivityThread( 5089): Added TimaKeyStore provider
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/ActivityManager( 1019): Display changed displayId=0
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1ff66f51 token=android.os.BinderProxy@14de6341 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1479): onStop
V/ActivityThread( 1479): updateVisibility : ActivityRecord{1ff66f51 token=android.os.BinderProxy@14de6341 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
E/SQLiteLog( 1621): (10) POSIX Error : 11 SQLite Error : 3850
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1019): [SO] activate (ident=0xb909f298, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Launcher( 1479): onTrimMemory. Level: 20
D/SensorManager( 1019): unregisterListener ::   
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb909f298, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 5057): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/WebViewFactory( 5089): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 5089): Loading: webviewchromium
,I/LibraryLoader( 5089): Time to load native libraries: 4 ms (timestamps 6896-6900)
I/LibraryLoader( 5089): Expected native library version number "",actual native library version number ""
,D/SensorService( 1019): [SO] currT = 66921017000, prevT = 66601227000, diff = 319790000, [-0.345 0.019 9.864]
,D/SensorService( 1019): [SO] -0.345 0.019 9.864
D/SensorService( 1019): [SO] [100 -> 255]
,V/WebViewChromiumFactoryProvider( 5089): Binding Chromium to main looper Looper (main, tid 1) {1ed566cd}
,I/LibraryLoader( 5089): Expected native library version number "",actual native library version number ""
,I/chromium( 5089): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5089): Initializing chromium process, renderers=0
,W/art     ( 5089): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5089): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 5089): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 5089): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 5089): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter( 5089): 901606274: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 5089): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5089): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5089): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5089): Local Branch: 
I/Adreno-EGL( 5089): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5089): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5089):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/chromium( 5089): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5089): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/8)
,W/art     ( 5089): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5089): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5089): *FMB* installDecor mIsFloating : false
,D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
D/PhoneWindow( 5089): *FMB* installDecor flags : 8456448
,E/SMD     (  288): DCD OFF
,D/SystemWebViewEngine( 5089): CordovaWebView is running on device made by: samsung
,W/art     ( 5089): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 5089): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5089): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 5089): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5089): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5089
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5089): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5089): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5089): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5089): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 5089): Timeline: Activity_idle id: android.os.BinderProxy@2fabb932 time:67436
,I/ActivityManager( 1019): Displayed Component not be shown by security: +779ms
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1019): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{141b42de u0 com.example.hello/.MainActivity t10} time:67457
,I/SamsungIME( 1765): getCurrentCandidateView
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1765): Dismiss ExpandCandiate
,I/chromium( 5089): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5089): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 5089): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1765): KeybaordView init() : load resources
,I/SurfaceFlinger(  257): id=11 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=11 Removed iello (-2/8)
,I/SamsungIME( 1765): getCurrentKeyboard
I/SamsungIME( 1765): getTextKeyboard
,D/SamsungIME( 1765): [SwiftkeyWrapper] currentLangauge : 1701729619,
,I/chromium( 5089): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5089): 
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/jxcore_app_log( 5089): JniHelper::setJavaVM(0xb8699448), pthread_self() = -1193465232
D/JX-Cordova( 5089): jxcore cordova android initializing
,W/jxcore-log( 5089): Initializing JXcore engine
,W/jxcore-log( 5089): JXcore engine is ready
,W/jxcore-log( 5089): Starting JXcore engine
,D/lights  ( 1019): button : 0 +
,E/audit   ( 1781): type=1400 msg=audit(1447834352.442:203): avc:  denied  { ioctl } for  pid=5089 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1781):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1781): type=1300 msg=audit(1447834352.442:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beff9d58 items=0 ppid=306 ppcomm=main pid=5089 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1781): type=1320 msg=audit(1447834352.442:203): 
,D/lights  ( 1019): button : 0 -
,W/jxcore-log( 5089): Platform android
W/jxcore-log( 5089): 
W/jxcore-log( 5089): Process ARCH arm
W/jxcore-log( 5089): 
,I/jxcore-log( 5089): JXcore Cordova bridge is ready!
I/jxcore-log( 5089): 
,W/jxcore-log( 5089): JXcore engine is started
,E/jxcore-log( 5089): >> samsung-SM-A300FU
E/jxcore-log( 5089): 
,I/jxcore-log( 5089): Total memory 1451114496,
I/jxcore-log( 5089): 
I/jxcore-log( 5089): Free memory 26865664
I/jxcore-log( 5089): 
I/jxcore-log( 5089): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5089): 
,I/jxcore-log( 5089): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5089): 
,I/jxcore-log( 5089): userPath [ 'www' ],
I/jxcore-log( 5089): 
,I/jxcore-log( 5089): Size 540 960,
I/jxcore-log( 5089): 
,I/jxcore-log( 5089): Screen Brightness 255,
I/jxcore-log( 5089): 
E/jxcore-log( 5089): Dummy Error Log.
E/jxcore-log( 5089): 
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{25c5dc0b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5089): getBuffer is called!!!!
I/jxcore-log( 5089): 
,E/SMD     (  288): DCD OFF
,D/SensorService( 1019): [SO] -0.345 0.019 9.864
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5089): disable()
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: false pid=5089, uid=10333
,D/SettingsProvider( 1019): name = wifi_on
,I/jxcore-log( 5089): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 5089): 
,I/jxcore-log( 5089): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5089): 
,E/SMD     (  288): DCD OFF,
,D/AndroidRuntime( 5146): 
D/AndroidRuntime( 5146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5146): CheckJNI is OFF
,D/AndroidRuntime( 5146): readGMSProperty: start
D/AndroidRuntime( 5146): readGMSProperty: already setted!!
D/AndroidRuntime( 5146): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5146): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5146): readGMSProperty: end
D/AndroidRuntime( 5146): addProductProperty: start
,E/AffinityControl( 5146): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5146): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1019): START PACKAGE DELETE: observer{265152819}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0,
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10333, uninstall pkg
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5089:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/WindowState( 1019): WIN DEATH: Window{2fcdea4a u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/7)
,D/InputDispatcher( 1019): Focus left window: 5089
,W/PackageSettings( 1019): Skipping PackageSetting{28cfce68 com.test.thalitest/10326} due to missing metadata,
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1019): Force removing ActivityRecord{141b42de u0 com.example.hello/.MainActivity t10}: app died, no saved state
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ActivityManager( 1019): Spurious death for ProcessRecord{82c04f0 5089:com.example.hello/u0a333}, curProc for 5089: null
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1479): onRestart, Launcher: 815651836
,I/art     ( 3601): Explicit concurrent mark sweep GC freed 2483(148KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 675us total 22.693ms
,D/Launcher( 1479): onStart, Launcher: 815651836
D/Launcher.HomeView( 1479): onStart
,D/Launcher( 1479): onResume, Launcher: 815651836
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1479): onResume
,I/art     ( 3004): Explicit concurrent mark sweep GC freed 340(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 967us total 29.849ms
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1765): mOCRHelper is null
,W/GeofencerStateMachine( 1641): Ignoring removeGeofence because network location is disabled.
,D/MenuAppsGridFragment( 1479): onResume
,D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  257): id=13 createSurf (540x960),1 flag=4, Mauncher
,I/KLMS-2.5.123: ( 3367): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 18 09:12:38 GMT+01:00 2015
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/InputDispatcher( 1019): Focus entered window: 1479
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 1479): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/KLMS-2.5.123: ( 3367): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
I/splitIntent( 1019): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 5089 uid 10333
,E/Zygote  ( 5162): MountEmulatedStorage()
,I/libpersona( 5162): KNOX_SDCARD checking this for 10090
E/Zygote  ( 5162): v2
I/libpersona( 5162): KNOX_SDCARD not a persona
I/SELinux ( 5162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 5162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5162 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageStatusReceiver( 4083): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3367): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3367): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SamsungIME( 1765): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/Zygote  ( 5172): MountEmulatedStorage()
I/libpersona( 5172): KNOX_SDCARD checking this for 10145
E/Zygote  ( 5172): v2
I/libpersona( 5172): KNOX_SDCARD not a persona
I/SELinux ( 5172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5172 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5172): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/FilterInstaller( 4954): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,D/Mms/FreeMessageReceiverService( 4083): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4083): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 5172): TimaSignature is unavailable
,I/TactileAssist( 1019): enable value -1
D/ActivityThread( 5172): Added TimaKeyStore provider
,I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,D/TimaKeyStoreProvider( 5162): TimaSignature is unavailable
,D/ActivityThread( 5162): Added TimaKeyStore provider
,I/TactileAssist( 1019): List of disabled apps :
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
D/RegisteredServicesCache( 1436): empty dynamic service
,I/KLMS-2.5.123: ( 3367): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 62394(3MB) AllocSpace objects, 17(386KB) LOS objects, 33% free, 22MB/34MB, paused 14.699ms total 232.237ms
,I/art     ( 1019): WaitForGcToComplete blocked for 22.510ms for cause Explicit
,I/FilterInstaller( 4954): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3367): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/FilterInstaller( 4954): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 4954): before removeFromFS
,I/KLMS-2.5.123: ( 3367): KLMSIntentService(): PACKAGE_REMOVED
I/ActivityManager( 1019): Displayed Component not be shown by security: +284ms (total +8s87ms)
I/KLMS-2.5.123: ( 3367): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3367): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3367): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3367): KLMSIntentService(): onDestroy()
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 11307(670KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.900ms total 169.778ms
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): WaitForGcToComplete blocked for 401.507ms for cause Explicit
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5196): MountEmulatedStorage()
E/Zygote  ( 5196): v2
I/libpersona( 5196): KNOX_SDCARD checking this for 10095
I/libpersona( 5196): KNOX_SDCARD not a persona
,I/SELinux ( 5196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5196): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5196 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/elm:15121( 5162): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5162): ELMEngine.ELMEngine( context ).
,D/TimaKeyStoreProvider( 5196): TimaSignature is unavailable
D/elm:15121( 5162): MDMBridge.setEnterpriseBridge()
,D/ActivityThread( 5196): Added TimaKeyStore provider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4910): onReceive() it will make start service
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10333
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
,E/Zygote  ( 5211): MountEmulatedStorage()
E/Zygote  ( 5211): v2
I/libpersona( 5211): KNOX_SDCARD checking this for 1000
I/libpersona( 5211): KNOX_SDCARD not a persona
,I/SELinux ( 5211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/SELinux ( 5211): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ThemeInfoUtil( 5172): getCurrentFestivalName is [null]
,D/ThemeInfoUtil( 5172): isCurrentFestival = false
,D/elm:15121( 5162): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10333
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1019): [SO] activate (ident=0xb909f298, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5211): TimaSignature is unavailable
,D/ActivityThread( 5211): Added TimaKeyStore provider
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb918aab8, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/elm:15121( 5162): ElmAgentService : onCreate()
,D/elm:15121( 5162): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5162): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5162): MDMBridge.getInstance()
D/elm:15121( 5162): MDMBridge.getAllLicenseInfoFromSDK()
,D/Compatibility( 4910): onHandleIntent()
,D/Compatibility( 4910): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10333, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/elm:15121( 5162): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5162): ElmAgentService : onDestroy().
,D/TaskPersister( 1019): removeObsoleteFile: deleting file=10_task.xml
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/Compatibility( 4910): found: 2
,D/Compatibility( 4910): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4910): skipping ResolveInfo{15abdce com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,D/Compatibility( 4910): considering ResolveInfo{14cbc4ef com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,D/Compatibility( 4910): default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4813): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4813): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 4813): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4813): Widget is not attached.
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,D/Compatibility( 4910): enabling receiver ResolveInfo{309ddbfc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/PreloadFilterInstaller( 5196): uses FILTER_DB_VER_1
,I/UpdateIcingCorporaServi( 3004): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,E/SQLiteLog( 5196): (284) automatic index on titles(filter_id)
,D/Compatibility( 4910): enabling receiver ResolveInfo{2d25a285 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{efd46fa u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:74513
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4910): enabling receiver ResolveInfo{2868e8da com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ContextImpl( 5211): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 10183(500KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 8.860ms total 281.896ms
,E/Zygote  ( 5231): MountEmulatedStorage()
I/libpersona( 5231): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5231): v2
I/libpersona( 5231): KNOX_SDCARD not a persona
,I/SELinux ( 5231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 4910): enabling receiver ResolveInfo{1e39c10b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/SELinux ( 5231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5231 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 4910): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 4848): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4848): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4848): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4848): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 5231): TimaSignature is unavailable
,D/ActivityThread( 5231): Added TimaKeyStore provider
E/Zygote  ( 5247): MountEmulatedStorage()
E/Zygote  ( 5247): v2
I/libpersona( 5247): KNOX_SDCARD checking this for 1000
I/libpersona( 5247): KNOX_SDCARD not a persona
I/SELinux ( 5247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5247 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 5247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 5196): (284) automatic index on titles(filter_id)
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 5247): TimaSignature is unavailable
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5247): Added TimaKeyStore provider
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1019): delete codoeFile: 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
I/AASA_removePackage( 1019): UID=10333 Target=com.example.hello
,D/PackageManager( 1019): result of delete: 1{265152819}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageBroadcastService( 1785): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1785): Clearing selected account for com.example.hello
,D/AndroidRuntime( 5146): Shutting down VM
,I/ActivityManager( 1019): Killing 4213:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UserAnalysis.PlaceProvider( 5231): PlaceProvider onCreate()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 5247): Received: android.intent.action.PACKAGE_REMOVED
,E/Zygote  ( 5267): MountEmulatedStorage(),
W/ContextImpl( 5247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  ( 5267): v2,
I/libpersona( 5267): KNOX_SDCARD checking this for 10032
,I/SELinux ( 5267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5267): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5267 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5267): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 4159:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/UserAnalysis.SecureDbManager( 5231): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5231): SecurePlaceDbHelper() 
D/UserAnalysis( 5231): Create SecureDbHelper
,I/art     (  306): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 893us total 28.704ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,E/JavaBinder( 1785): !!! FAILED BINDER TRANSACTION !!!
E/Icing   ( 1785): Service broker callback failed: android.os.TransactionTooLargeException
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.031ms
,D/TimaKeyStoreProvider( 5267): TimaSignature is unavailable
,D/ActivityThread( 5267): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Choreographer( 1479): Skipped 47 frames!  The application may be doing too much work on its main thread.
,D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/IntelligenceServiceApplication( 5231): onCreate(),
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5231): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/IntelligenceServiceApplication( 5231): no applications having user consent for prediction
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 26.839ms
D/AcmsService( 5247): Enter Oncreate
D/AcmsServiceMonitor( 5247): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5247): creating AcmsCore
D/AcmsCore( 5247): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5247): AcmsCore
,I/LocationSettingsChecker( 1785): Removing dialog suppression flag for package com.example.hello
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsCore( 5247): init
,D/AcmsCore( 5247): Looper handler is not null
D/AcmsCore( 5247): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5247): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5247): Incrementing - Counter value: 1
D/AcmsCore( 5247): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5247): onStartCommand
D/AcmsService( 5247): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 5247): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5247): Incrementing - Counter value: 2
D/AcmsService( 5247): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 5247): AcmsCertificateMngr
,D/ActivityThread( 5247): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@14de6341 time:74805
,D/AcmsRevocationMngr( 5247): AcmsRevocationMngr
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::stopService] Service stopped.
,I/UpdateIcingCorporaServi( 3004): UpdateCorporaTask done [took 314 ms] updated apps [took 314 ms] 
W/ContextImpl( 3578): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
,D/gH_CompatibleDatabase( 1785): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/SensorService( 1019): [SO] currT = 74831298000, prevT = 74411061000, diff = 420237000, [-0.326 0.038 9.864]
D/SensorService( 1019): [SO] -0.326 0.038 9.864
D/gH_CompatibleDatabase( 1785): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/SensorService( 1019): [SO] [100 -> 255]
,D/gH_MetricsDatabase( 1785): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1785): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1785): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1785): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1785): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/gH_CompatibleDatabase( 1785): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1785): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1785): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1785): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1785): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1785): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AcmsService( 5247): Inside handle Intent
D/AcmsService( 5247): App removed - package name: com.example.hello
D/AcmsCore( 5247): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5247): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5247): Incrementing - Counter value: 3
D/AcmsCore( 5247): Incremented Counter Value: postToAcmsCoreHandler =>5
D/AcmsService( 5247): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5247): Decrementing - Counter value: 2
,W/art     ( 5146): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,D/RCPManager( 4531):  in createShortcut() for packageName: com.example.hello userId0
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1019):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
,D/BluetoothAdapter( 5231): 1061249767: getState() :  mService = null. Returning STATE_OFF,
V/PlaceDetection v1.0.19 ( 5231): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,E/Zygote  ( 5291): MountEmulatedStorage()
,I/ActivityManager( 1019): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/FilterUnInstaller( 4954): FilterUninstaller.java : removeFromDB()
,E/Zygote  ( 5291): v2,
I/libpersona( 5291): KNOX_SDCARD checking this for 1000
I/libpersona( 5291): KNOX_SDCARD not a persona
,V/PlaceDetection v1.0.19 ( 5231): [PlaceDetection::stopService] Service stopped.,
V/PlaceDetection v1.0.19 ( 5231): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/NetworkScheduler.SchedulerReceiver( 1621): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1621): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/SELinux ( 5291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/FilterProvider( 5196): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 5196): packageName : com.example.hello
,I/SELinux ( 5291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Killing 3559:com.google.android.talk/u0a102 (adj 15): empty #31
,E/SELinux ( 5291): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 4954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,I/ActivityManager( 1019): Killing 4562:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4577:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5291): TimaSignature is unavailable
,D/ActivityThread( 5291): Added TimaKeyStore provider
,E/SPPClientService( 5267): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5267): [PushClientApplication] Push log off : This is Ship build version
,I/SA      ( 4921): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4921): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10333 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1019): Killing 4679:com.google.android.gms:car/u0a11 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/SPPClientService( 5267): PushLog.txt file is not deleted.
,D/SPPClientService( 5267): PushLog.txt file is not deleted.
D/PopupuiReceiver( 5291): onReceive() getAction : android.intent.action.PACKAGE_REMOVED
D/SPPClientService( 5267): ============PushLog. stop!
,I/PackagesMonitor( 4229): PackagesMonitor onReceive :com.example.hello
,D/SecContentProvider2( 1019): uri = -1 selection = getSealedState
,D/SecContentProvider2( 1019): mCursor = null
,I/PopupuiReceiver_KNOX( 5291): getSealedState : true
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
D/SecContentProvider2( 1019): uri = 15 selection = getSealedHideNotificationMessages
,D/SecContentProvider2( 1019): mCursor = null
,I/PopupuiReceiver_KNOX( 5291): getSealedHideNotificationMessages : 1
,D/SecContentProvider2( 1019): uri = 15 selection = getCheckCoverPopupState,
D/SecContentProvider2( 1019): mCursor = null
,I/PopupuiReceiver_KNOX( 5291): getCheckCoverPopupState : true
,D/PopupuiReceiver( 5291): Action package removed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GMPM-SVC( 1785): App measurement is starting up
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1785): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1785): CP2 sync disabled
,W/libprocessgroup( 1019): failed to open /acct/uid_10035/pid_4213/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10108/pid_4159/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10065/pid_4562/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10011/pid_4679/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4577/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_3559/cgroup.procs: No such file or directory
,I/splitIntent( 1019): Queue : background intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1019): Killing 4830:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5316): MountEmulatedStorage()
,E/Zygote  ( 5316): v2
I/libpersona( 5316): KNOX_SDCARD checking this for 10086
I/libpersona( 5316): KNOX_SDCARD not a persona
,I/SELinux ( 5316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5316 uid=10086 gids={50086, 9997} abi=armeabi-v7a
,I/SELinux ( 5316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5316): TimaSignature is unavailable
,D/ActivityThread( 5316): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_4830/cgroup.procs: No such file or directory
,D/ConnectivityManager( 1785): CallingUid : 10011, CallingPid : 1785
,D/ConnectivityService( 1019): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5333): MountEmulatedStorage()
,E/Zygote  ( 5333): v2
I/libpersona( 5333): KNOX_SDCARD checking this for 10007
I/libpersona( 5333): KNOX_SDCARD not a persona
,E/SQLiteLog( 5316): (28) failed to open "/data/data/com.android.documentsui/databases/recents.db" with flag (131138) and mode_t (0) due to error (30)
,I/SELinux ( 5333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5333 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 5333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5333): TimaSignature is unavailable
,D/ActivityThread( 5333): Added TimaKeyStore provider
,E/SQLiteDatabase( 5316): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5316): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5316): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5316): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5316): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:312)
E/SQLiteDatabase( 5316): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:266)
E/SQLiteDatabase( 5316): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:382)
E/SQLiteDatabase( 5316): 	at android.content.ContentResolver.call(ContentResolver.java:1425)
E/SQLiteDatabase( 5316): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 5316): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
E/SQLiteDatabase( 5316): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
E/SQLiteDatabase( 5316): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
E/SQLiteDatabase( 5316): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5316): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5316): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5316): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5316): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5316): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5316): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime( 5316): Shutting down VM
E/AndroidRuntime( 5316): FATAL EXCEPTION: main
E/AndroidRuntime( 5316): Process: com.android.documentsui, PID: 5316
E/AndroidRuntime( 5316): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5316): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
E/AndroidRuntime( 5316): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
E/AndroidRuntime( 5316): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
E/AndroidRuntime( 5316): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5316): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5316): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 5316): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5316): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5316): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 5316): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 5316): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 5316): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 5316): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5316): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:312)
E/AndroidRuntime( 5316): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:266)
E/AndroidRuntime( 5316): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:382)
E/AndroidRuntime( 5316): 	at android.content.ContentResolver.call(ContentResolver.java:1425)
E/AndroidRuntime( 5316): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 5316): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
E/AndroidRuntime( 5316): 	... 9 more
I/ActivityManager( 1019): Killing 4868:com.policydm/1000 (adj 15): empty #31
I/ActivityManager( 1019): Killing 4784:com.google.android.partnersetup/u0a14 (adj 15): empty #32

```
