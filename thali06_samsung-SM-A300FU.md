#### Test 623445121bdd37c_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/lights  ( 1019): write_int failed to open -1
--------- beginning of system
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
D/BatteryService( 1019): turn on LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId -1 pkgname com.android.systemui
I/ValidateNoPeople( 1019): skipping global notification
D/WindowManager( 1019): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1179
I/PowerManagerService( 1019): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1019): Waking up from sleep (uid 10049)...
V/KeyguardServiceDelegate( 1019): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1ce33dc0)
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1019): [s] UserActivityState : 0 -> 1
D/KeyguardViewMediator( 1179): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1179): notifyScreenOnLocked
D/Launcher( 1476): onRestart, Launcher: 702283679
I/DisplayPowerController( 1019): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1019): sensor enabled
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 160 -> 160
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
D/DisplayPowerController( 1019): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1019): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb85b7d18, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/libsuspend( 1019): !@autosuspend_wakeup_count_disable
I/libsuspend( 1019): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1019): !@display_state: OFF -> ON
D/SurfaceFlinger(  258): Set power mode=2, type=0 flinger=0xb8aaa690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 2 on display: 0
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
I/DisplayManagerService( 1019): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/ActivityManager( 1019): Display changed displayId=0
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/Launcher( 1476): onStart, Launcher: 702283679
D/Launcher.HomeView( 1476): onStart
D/StatusBarKeyguardViewManager( 1179): onScreenTurnedOn()
D/KeyguardViewMediator( 1179): handleNotifyScreenOn
D/SecKeyguardClockSingleView( 1179): onScreenTurnedOn
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/PalmMotion( 1019): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1019): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1019): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1019): [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
E/lights  ( 1019): write_int failed to open -1
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
V/ActivityManager( 1019): Display changed displayId=0
D/Launcher( 1476): onResume, Launcher: 702283679
D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1476): onResume
D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
D/SamsungIME( 1742): showDlgMsgBox : false true true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/NfcService( 1438): call the applyRouting
D/MenuAppsGridFragment( 1476): onResume
D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
E/lights  ( 1019): write_led_info failed to open -1
D/BatteryService( 1019): turn off LED
E/lights  ( 1019): write_led_info failed to open -1
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1019): write_led_info failed to open -1
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
E/lights  ( 1019): write_led_info failed to open -1
W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1019): fail to set sysfs 1
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
D/KnoxNotification( 1179): ----- inflateViews : modified publicViewLocal -----
D/InputMethodManagerService( 1019): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_ON
E/MotionRecognitionService( 1019):  handler : SCREEN_ON end
D/KnoxNotification( 1179): ----- inflateViews : modified KnoxViewLocal -----
I/WifiNative-HAL( 1019): startHal
D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/NotificationService( 1019): ACTION_SCREEN_ON
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9d45d7fc
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
I/WifiNative-HAL( 1019): Could not start hal
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PersonaManager( 1179): PersonaID is invalid or persona doesn't exists. : -1
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/KeyguardServiceDelegate( 1019): **** SHOWN CALLED ****
I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@11aa4618 time:66169
D/DisplayPowerController( 1019): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController( 1019): Unblocked screen on after 158 ms
D/DisplayPowerState( 1019): !@ ColorFade exit
V/UserPresentBroadcastReceiver( 1690): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/StatusBarKeyguardViewManager( 1179): callback.onShown()
D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/SurfaceFlinger(  258): id=10 Removed DolorFade (8/8)
I/SurfaceFlinger(  258): id=10 Removed DolorFade (-2/8)
E/libEGL  ( 1019): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1019): Excessive delay in ColorFade : dismiss: 14ms
D/lights  ( 1019): lcd : 160 +
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 160 -> 160
D/lights  ( 1019): lcd : 160 -
D/DisplayPowerController( 1019): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1019): animation target = 160, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1019): SecHardwareInterface.setBatteryADC : true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/GalleryCacheReady( 4387): Receive : home resume
D/BatteryMeterView( 1179): onDraw batteryColor : -1
D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1019): Bridge Server is not available
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/Recents_RecreateReceiver( 2285): onReceive by home
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/TaskCloserActivity( 4965): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/SensorService( 1019): [SO] currT = 66231240000, prevT = 50773574000, diff = 15457666000, [-0.326 -0.115 9.941]
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 4244): ui event
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 2 on display 0
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 1
D/PowerManagerService( 1019): Excessive delay in !@display_state: ON: 233ms
D/SurfaceControl( 1019): Excessive delay in setPowerMode(): 232ms
I/libpersona( 5298): KNOX_SDCARD checking this for 10135
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event1/device/enabled: 1
I/libpersona( 5298): KNOX_SDCARD not a persona
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event3/device/enabled: 1
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
E/Zygote  ( 5298): MountEmulatedStorage()
E/Zygote  ( 5298): v2
I/SELinux ( 5298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5298 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 5298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManagerService( 1019): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_ON called
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/AndroidRuntime( 5286): 
D/AndroidRuntime( 5286): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/AndroidRuntime( 5286): CheckJNI is OFF
D/AndroidRuntime( 5286): readGMSProperty: start
D/AndroidRuntime( 5286): readGMSProperty: already setted!!
D/AndroidRuntime( 5286): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5286): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5286): readGMSProperty: end
D/AndroidRuntime( 5286): addProductProperty: start
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1438): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1438): call the applyRouting
D/TimaKeyStoreProvider( 5298): TimaSignature is unavailable
D/ActivityThread( 5298): Added TimaKeyStore provider
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
D/accuweather( 1579): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1579): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1579): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1579): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1579): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1579): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1579): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1579): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
W/ResourcesManager( 5298): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5298): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5298): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5298): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5298): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/accuweather( 1579): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1579): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
E/accuweather( 1579): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 07 25
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event3/device/enabled: 1
I/SamsungIME( 1742): getNextShiftState() cursorCapsMode : 0
W/OpenGLRenderer( 1476): SFEffectCache::get: create texture(0xa1ef0724): name, size, mSize = 33, 85680, 216692
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1019): Killing 4899:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Broadcasts
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1019): Excessive delay in MISC setInteractive(true) while turning screen on: 161ms
I/QCOM PowerHAL( 1019): Got set_interactive hint
D/PowerManagerService( 1019): Excessive delay in nativeSetInteractive(true): 163ms
D/PowerManagerService( 1019): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 398ms
D/lights  ( 1019): button : 1 +
D/SSRM:n  ( 1019): SIOP:: AP = 330
D/SensorService( 1019): [SO] currT = 66431097000, prevT = 50773574000, diff = 15657523000, [-0.345 -0.115 9.941]
D/SensorService( 1019): [SO] -0.345 -0.115 9.941
D/SensorService( 1019): [SO] [100 -> 255]
D/lights  ( 1019): button : 1 -
D/daemonapp( 1634): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1634): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/AffinityControl( 5286): AffinityControl: registerfunction enter
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1634): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1634): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1634): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1634): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457612640000
D/daemonapp( 1634): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457591104629
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1634): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1634): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1634): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1634): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1634): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/AndroidRuntime( 5286): Calling main entry com.android.commands.am.Am
E/daemonapp( 1634): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4899/cgroup.procs: No such file or directory
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/Launcher.HomeView( 1476): onPause
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1476
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
D/AndroidRuntime( 5286): Shutting down VM
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
V/TaskCloserActivity( 4965): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 5324): MountEmulatedStorage()
E/Zygote  ( 5324): v2
I/libpersona( 5324): KNOX_SDCARD checking this for 10346
I/libpersona( 5324): KNOX_SDCARD not a persona
I/SELinux ( 5324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5324 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5324): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1476): updateVisibility : ActivityRecord{251ac04c token=android.os.BinderProxy@11aa4618 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 5324): TimaSignature is unavailable
D/ActivityThread( 5324): Added TimaKeyStore provider
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/ActivityManager( 1019): Display changed displayId=0
D/Launcher.HomeView( 1476): onStop
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1476): updateVisibility : ActivityRecord{251ac04c token=android.os.BinderProxy@11aa4618 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1019): [SO] activate (ident=0xb85b7d18, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Launcher( 1476): onTrimMemory. Level: 20
D/SensorManager( 1019): unregisterListener ::   
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb85b7d18, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/WebViewFactory( 5324): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5324): Time to load native libraries: 2 ms (timestamps 6737-6739)
I/LibraryLoader( 5324): Expected native library version number "",actual native library version number ""
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 5286): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,V/WebViewChromiumFactoryProvider( 5324): Binding Chromium to main looper Looper (main, tid 1) {171a02fd}
I/LibraryLoader( 5324): Expected native library version number "",actual native library version number ""
I/chromium( 5324): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5324): Initializing chromium process, singleProcess=true
W/art     ( 5324): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5324): ApplicationContext is null in ApplicationStatus
D/SensorService( 1019): [SO] -0.345 -0.115 9.941
D/SensorService( 1019): [SO] [100 -> 255]
W/chromium( 5324): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5324): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5324): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5324): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5324): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5324): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5324): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5324): Local Branch: 
I/Adreno-EGL( 5324): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5324): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5324):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5324): 702283679: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5324): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5324): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5324): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5324): *FMB* installDecor flags : 8456448
I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/8)
I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/8)
D/SystemWebViewEngine( 5324): CordovaWebView is running on device made by: samsung
W/art     ( 5324): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5324): Attempt to remove local handle scope entry from IRT, ignoring
E/SMD     (  289): DCD OFF
D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
D/OpenGLRenderer( 5324): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
W/chromium( 5324): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 5324): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5324): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 5324
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5324): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5324): Initialized EGL, version 1.4
D/OpenGLRenderer( 5324): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5324): Enabling debug mode 0
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1019): Displayed Component not be shown by security: +781ms
D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{67dfbf9 u0 com.example.hello/.MainActivity t22} time:67325
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/Timeline( 5324): Timeline: Activity_idle id: android.os.BinderProxy@1c452b69 time:67328
I/SamsungIME( 1742): getCurrentCandidateView
D/SamsungIME( 1742): Dismiss ExpandCandiate
W/BindingManager( 5324): Cannot call determinedVisibility() - never saw a connection for the pid: 5324
I/SamsungIME( 1742): getDebugLevel  : 0x4f4c
,I/chromium( 5324): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1742): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1742): KeybaordView init() : load resources
,I/SamsungIME( 1742): getCurrentKeyboard
I/SamsungIME( 1742): getTextKeyboard
,I/SurfaceFlinger(  258): id=11 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=11 Removed iello (-2/8)
,D/SamsungIME( 1742): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/JsMessageQueue( 5324): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5324): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5324): JniHelper::setJavaVM(0xb7e67448), pthread_self() = -1204029584
,D/JX-Cordova( 5324): jxcore cordova android initializing
,D/lights  ( 1019): button : 0 +
,D/lights  ( 1019): button : 0 -
,W/jxcore-log( 5324): Initializing JXcore engine
,W/jxcore-log( 5324): JXcore engine is ready
,W/jxcore-log( 5324): Starting JXcore engine
,E/audit   ( 1796): type=1400 msg=audit(1457591106.180:203): avc:  denied  { ioctl } for  pid=5324 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1796):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1796): type=1300 msg=audit(1457591106.180:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be8d5d58 items=0 ppid=306 ppcomm=main pid=5324 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1796): type=1320 msg=audit(1457591106.180:203): 
,W/jxcore-log( 5324): Platform android
W/jxcore-log( 5324): 
W/jxcore-log( 5324): Process ARCH arm
W/jxcore-log( 5324): 
,I/jxcore-log( 5324): JXcore Cordova bridge is ready!
I/jxcore-log( 5324): 
,W/jxcore-log( 5324): JXcore engine is started,
,E/jxcore-log( 5324): >> samsung-SM-A300FU
E/jxcore-log( 5324): 
,I/jxcore-log( 5324): Total memory 1451114496
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): Free memory 22016000
I/jxcore-log( 5324): 
I/jxcore-log( 5324): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): userPath [ 'www', 'www' ]
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): Size 540 960
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): Screen Brightness 160
I/jxcore-log( 5324): 
,E/jxcore-log( 5324): Dummy Error Log.
E/jxcore-log( 5324): 
,I/jxcore-log( 5324): getBuffer is called!!!!
I/jxcore-log( 5324): 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{23e9dac4 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  289): DCD OFF
,D/SensorService( 1019): [SO] -0.326 -0.115 9.922,
,E/SMD     (  289): DCD OFF
,D/BluetoothAdapter( 5324): disable()
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: false pid=5324, uid=10346
,D/SettingsProvider( 1019): name = wifi_on
,I/jxcore-log( 5324): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 5324): 
,I/jxcore-log( 5324): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5324): 
,D/AndroidRuntime( 5376): ,
D/AndroidRuntime( 5376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5376): CheckJNI is OFF,
D/AndroidRuntime( 5376): readGMSProperty: start
D/AndroidRuntime( 5376): readGMSProperty: already setted!!,
D/AndroidRuntime( 5376): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5376): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5376): readGMSProperty: end
D/AndroidRuntime( 5376): addProductProperty: start
,E/AffinityControl( 5376): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5376): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{1042222850}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10346, uninstall pkg,
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5324:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{21d3de49 com.test.thalitest/10338} due to missing metadata
,W/ActivityManager( 1019): Force removing ActivityRecord{67dfbf9 u0 com.example.hello/.MainActivity t22}: app died, no saved state
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 5324
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/7),
I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7,
,W/ActivityManager( 1019): mDVFSHelper.acquire(),
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10346 user=0: pkg removed
,D/Launcher( 1476): onRestart, Launcher: 702283679
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1476): onStart, Launcher: 702283679
,D/Launcher.HomeView( 1476): onStart
D/Launcher( 1476): onResume, Launcher: 702283679
,D/SettingsProvider( 1019): name = kids_home_mode
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1476): onResume
,I/art     ( 3766): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 698us total 24.778ms
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4082): Explicit concurrent mark sweep GC freed 22584(1675KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.148ms total 65.501ms
,D/MenuAppsGridFragment( 1476): onResume
,D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,E/SamsungIME( 1742): mOCRHelper is null
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.5.123: ( 3415): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 07:25:12 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/InputDispatcher( 1019): Focus entered window: 1476
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1476): log_dcs ThreadedRenderer::initialize entered! 
,I/KLMS-2.5.123: ( 3415): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3415): KLMSIntentService(): onCreate()
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 5324 uid 10346
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.123: ( 3415): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3415): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
I/libpersona( 5392): KNOX_SDCARD checking this for 10090,
E/Zygote  ( 5392): MountEmulatedStorage(),
I/libpersona( 5392): KNOX_SDCARD not a persona
E/Zygote  ( 5392): v2
I/SELinux ( 5392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5392 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,D/SamsungIME( 1742): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/KLMS-2.5.123: ( 3415): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/art     (  306): Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 21.470ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.978ms
I/KLMS-2.5.123: ( 3415): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3415): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3415): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello,
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 17.116ms
,D/TimaKeyStoreProvider( 5392): TimaSignature is unavailable
D/ActivityThread( 5392): Added TimaKeyStore provider
,D/RegisteredServicesCache( 1438): empty dynamic service
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 68784(4MB) AllocSpace objects, 17(386KB) LOS objects, 33% free, 23MB/35MB, paused 2.442ms total 218.454ms
,I/art     ( 1019): WaitForGcToComplete blocked for 37.966ms for cause Explicit
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3415): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3415): KLMSIntentService(): onDestroy()
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10346
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello,
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1019): removeObsoleteFile: deleting file=22_task.xml
V/EnterpriseBillingPolicy( 1019): uID is 10346
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1019): [SO] activate (ident=0xb85b7d18, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1019): [SO] changed settle time [0]
,D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb85b7d18, enabled=1)
D/SensorService( 1019): [SO] AR_init
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 10771(577KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 11.750ms total 176.047ms
,I/art     ( 1019): WaitForGcToComplete blocked for 385.310ms for cause Explicit
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PersonaManager( 1019): isKioskContainerExistOnDevice
,I/ActivityManager( 1019): Displayed Component not be shown by security: +444ms (total +8s316ms)
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1019): no available spell checker services found
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/elm:15121( 5392): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5392): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5392): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5392): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5392): ElmAgentService : onCreate()
,D/elm:15121( 5392): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5392): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5392): MDMBridge.getInstance()
D/elm:15121( 5392): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5392): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 5067): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5067): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5067): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5067): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5136): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5136): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/elm:15121( 5392): ElmAgentService : onDestroy().
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 1019): Killing 4922:com.wssyncmldm/1000 (adj 15): empty #31
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackagesMonitor( 4387): PackagesMonitor onReceive :com.example.hello
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/FreeMessageStatusReceiver( 4244): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 7613(478KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 14.966ms total 195.401ms
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4244): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4244): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1019): List of disabled apps :
,D/PackageManager( 1019): delete codoeFile: 
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
I/AASA_removePackage( 1019): UID=10346 Target=com.example.hello
D/PackageManager( 1019): result of delete: 1{1042222850}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 5376): Shutting down VM
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4922/cgroup.procs: No such file or directory
,D/Compatibility( 5116): onReceive() it will make start service
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5116): onHandleIntent()
,D/Compatibility( 5116): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5116): found: 2
D/Compatibility( 5116): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5116): skipping ResolveInfo{e88d1f9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5116): considering ResolveInfo{3fd1753e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5116): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5116): enabling receiver ResolveInfo{29dbff9f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
E/Zygote  ( 5413): MountEmulatedStorage()
E/Zygote  ( 5413): v2
I/libpersona( 5413): KNOX_SDCARD checking this for 10055
I/libpersona( 5413): KNOX_SDCARD not a persona
,I/SELinux ( 5413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/Compatibility( 5116): enabling receiver ResolveInfo{2e8878ec com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SELinux ( 5413): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5413 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5116): enabling receiver ResolveInfo{177b94b5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5116): enabling receiver ResolveInfo{1feba74a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5116): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5413): TimaSignature is unavailable
,D/ActivityThread( 5413): Added TimaKeyStore provider
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/UserAnalysis.PlaceProvider( 5413): PlaceProvider onCreate()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/SensorService( 1019): [SO] currT = 74711055000, prevT = 74231057000, diff = 479998000, [-0.345 -0.115 9.922]
,D/SensorService( 1019): [SO] -0.345 -0.115 9.922
D/SensorService( 1019): [SO] [100 -> 255]
,D/UserAnalysis.SecureDbManager( 5413): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5413): SecurePlaceDbHelper() 
D/UserAnalysis( 5413): Create SecureDbHelper
,I/Choreographer( 1476): Skipped 40 frames!  The application may be doing too much work on its main thread.
,D/IntelligenceServiceApplication( 5413): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5413): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ContextImpl( 4462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/IntelligenceServiceApplication( 5413): no applications having user consent for prediction
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5430): MountEmulatedStorage()
E/Zygote  ( 5430): v2
I/libpersona( 5430): KNOX_SDCARD checking this for 1000
I/libpersona( 5430): KNOX_SDCARD not a persona
I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@11aa4618 time:74754
I/SELinux ( 5430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 5376): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{9b706d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:74772
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,I/ActivityManager( 1019): Killing 4309:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/BluetoothAdapter( 5413): 348450326: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 5413): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5413): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5413): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/TimaKeyStoreProvider( 5430): TimaSignature is unavailable
,D/ActivityThread( 5430): Added TimaKeyStore provider
,W/ResourcesManager( 5430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 5413): (10) unixWrite() File Descriptor : 25 gets errno : 9
,D/RCPManager( 5430):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1019):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5413): (10) unixWrite() File Descriptor : 25 gets errno : 9
,E/SQLiteDatabase( 5413): Error inserting timestamp=1457591112897 message=Predictor: service is stopped by Application.onCreate
E/SQLiteDatabase( 5413): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5413): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5413): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5413): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5413): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5413): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5413): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5413): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5413): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5413): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5413): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5413): It failed to insert to dump_log table
,E/SQLiteLog( 5413): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5413): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 5413): Error inserting timestamp=1457591112953 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 5413): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5413): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5413): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5413): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5413): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5413): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5413): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5413): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5413): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5413): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5413): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5413): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5413): It failed to insert to dump_log table
,D/FilterInstaller( 5176): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5176): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5176): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5176): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5176): before removeFromFS
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1019): failed to open /acct/uid_10108/pid_4309/cgroup.procs: No such file or directory
,E/Zygote  ( 5447): MountEmulatedStorage()
,E/Zygote  ( 5447): v2
I/libpersona( 5447): KNOX_SDCARD checking this for 10095
I/libpersona( 5447): KNOX_SDCARD not a persona,
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5447 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
I/SELinux ( 5447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5456): MountEmulatedStorage()
E/Zygote  ( 5456): v2
I/libpersona( 5456): KNOX_SDCARD checking this for 1000
I/libpersona( 5456): KNOX_SDCARD not a persona
,I/SELinux ( 5456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5447): TimaSignature is unavailable
,D/ActivityThread( 5447): Added TimaKeyStore provider

```
