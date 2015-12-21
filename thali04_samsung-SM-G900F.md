#### Test 506502782e2cb10_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
V/BitmapFactory( 7098): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_translator_normal.pkm
V/BitmapFactory( 7098): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_press.pkm
V/BitmapFactory( 7098): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_focus.pkm
V/BitmapFactory( 7098): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_disable.pkm
V/BitmapFactory( 7098): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_normal.pkm
E/LightSensor(  922): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  922): mCallbacks.updateBrightness()
D/DisplayPowerController(  922): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/PowerManagerService(  922): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  922): Nap time (uid 1000)...
I/PowerManagerService(  922): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  922): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  922): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  922): setDeviceInteractive: 0
D/PowerManagerService(  922): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  922): handleSandman : startDream()
E/PowerManagerService(  922): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  922): Sleeping (uid 1000)...
D/PowerManagerService(  922): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  922): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  922): [input device light] handleInputDeviceLightOff
D/InputManager-JNI(  922): sysfs_write +: /sys/class/input/event1/device/enabled: 0
I/SurfaceFlinger(  257): id=15 createSurf (1080x1920),2 flag=404, ColorFade
D/InputManager-JNI(  922): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  922): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  922): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/SContextService(  922): 	.unregisterCallback : 1, client=
D/SContextService(  922): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@27dad398, Service = Auto Rotation, used = 1
W/CAE     (  922): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  922): stop(ContextProvider.java:149)
V/CAE     (  922): clear(AutoRotationRunner.java:182)
V/CAE     (  922): disable(AutoRotationRunner.java:171)
I/CAE     (  922): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  922): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  301): sendContextData: -78, 7, 0, 0
D/CAE     (  922): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  922): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/CAE     (  922): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
D/DisplayPowerController(  922): ColorFade: onAnimationStart
I/CAE     (  922): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/DisplayPowerController(  922): getFinalBrightness : 8 -> 0
D/CAE     (  922): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  922): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  922): removeSContextService() : service = Auto Rotation
D/SContextService(  922): ===== SContext Service List =====
D/SContextManager(  922):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@28f65b1, service=Auto Rotation
D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): timeout : 5000
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SQLiteSecureOpenHelper( 3477): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3477): getDatabaseLocked(b,b,pwd)...
D/DisplayPowerController(  922): getFinalBrightness : 8 -> 0
D/lights  (  922): lcd : 0 +
D/lights  (  922): lcd : 0 -
E/LightSensor(  922): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  922): mCallbacks.updateBrightness()
D/DisplayPowerController(  922): getFinalBrightness : 8 -> 0
D/Mms/BubbleViewCache( 7098): fillCache bubble = 8
D/Mms/Synchronizer( 7098): [start]    doSync consume time = 312.040312
D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 7098
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 0.987 ms
D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1181): handleNotifyScreenOff
D/TP/MmsSmsProvider( 1464): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1464): syncDBData start
V/TP/MmsSmsProvider( 1464): syncDBData sms end
V/TP/MmsSmsProvider( 1464): syncDBData mms end
V/TP/MmsSmsProvider( 1464): syncDBData end
D/LightsService(  922): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 922) 
D/LightsService(  922): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService(  922): [SvcLED]  onSensorChanged::light value = 0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/SensorManager(  922): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  922): unregisterListener ::   
D/lights  (  922): led_pattern : 5 +
D/BatteryService(  922): turn on LED for fully charged
E/Zygote  ( 7143): MountEmulatedStorage()
E/Zygote  ( 7143): v2
I/libpersona( 7143): KNOX_SDCARD checking this for 10077
I/libpersona( 7143): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7143 uid=10077 gids={50077, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 7098): [end]    doSync consume time = 42.192343
D/lights  (  922): led_pattern : 5 -
D/LightsService(  922): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/CAE     (  922): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  922): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
D/AndroidRuntime( 7135): 
D/AndroidRuntime( 7135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/CAE     (  922): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  922): SendSensorHubData: send data = -76, 13, -46, 0
D/AndroidRuntime( 7135): CheckJNI is OFF
D/AndroidRuntime( 7135): setted country_code = Poland
D/AndroidRuntime( 7135): setted countryiso_code = PL
D/AndroidRuntime( 7135): setted sales_code = XEO
D/AndroidRuntime( 7135): readGMSProperty: start
D/AndroidRuntime( 7135): readGMSProperty: already setted!!
D/AndroidRuntime( 7135): readGMSProperty: end
D/AndroidRuntime( 7135): addProductProperty: start
D/Sensorhubs(  301): sendContextData: -76, 13, -46, 0
I/SELinux ( 7143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7143): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/CAE     (  922): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 22, 15, 28,
D/SensorHubManager(  922): SendSensorHubData: send data = -63, 14, 22, 15, 28
D/Sensorhubs(  301): sendContextData: -63, 14, 22, 15, 28
D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  922):  handler : SCREEN_OFF end 
D/TimaKeyStoreProvider( 7143): TimaSignature is unavailable
D/ActivityThread( 7143): Added TimaKeyStore provider
D/NotificationService(  922): ACTION_SCREEN_OFF
D/LightsService(  922): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 922) 
D/LightsService(  922): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  922): [SvcLED]  onSensorChanged::light value = 0
D/WifiStateMachine(  922): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  922): handleScreenStateChanged Exit: false
E/WifiStateMachine(  922): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  922): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  922): do suspend true
D/SensorManager(  922): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  922): unregisterListener ::   
D/LightsService(  922): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/voice   (  295): voice_set_parameters: enter: screen_state=off
V/voice   (  295): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  295): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  295): adev_set_parameters: exit
D/ResourcesManager( 7143): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
I/SecExternalDisplayIntents_Java(  922): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/IpRemoteDisplayController(  922): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  922): Bridge Server is not available
D/BadgeProvider( 7143): onCreate
D/BadgeProvider( 7143): DatabaseHelper
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1181): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/PersonaManagerService(  922): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  922): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1458): call the applyRotuiing
D/STATUSBAR-PhoneStatusBar( 1181):      ACTION_SCREEN_OFF is finished!!!! 
D/Mms/MessagingNotification( 7098): checkBadgeCount unreadCount=0 badgeCount=0
E/LightSensor(  922): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  922): mCallbacks.updateBrightness()
D/DisplayPowerController(  922): getFinalBrightness : 8 -> 0
D/TP/SmsProvider( 1464): query,matched:26, calling pid = 7098
D/DisplayPowerState(  922): !@ ColorFade entry
D/DisplayPowerController(  922): ColorFade: onAnimationEnd
D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.894 ms
E/StatusBar( 1181): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1181): dismissHelpPopup 
D/AutomaticBrightnessController(  922): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  922): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  922): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  922): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  922): Light old sensor_state 513, new sensor_state : 1 en : 0
D/accuweather( 1941): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1941): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1941): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
E/AffinityControl( 7135): AffinityControl: registerfunction enter
D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 7098
D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 0.985 ms
D/SensorManager(  922): unregisterListener ::   
E/Sensors (  922): Acc old sensor_state 1, new sensor_state : 0 en : 0
I/Mms/ReservationManager( 7098): ReservationManager()
I/Mms/ReservationManager( 7098): resetAfterConnected()
D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 7098
D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 1.164 ms
D/DisplayPowerController(  922): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  922): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  922): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
D/AndroidRuntime( 7135): Calling main entry com.android.commands.am.Am
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
V/ActivityManager(  922): Display changed displayId=0
D/SensorManager(  922): unregisterListener ::   
I/Mms/ReservationManager( 7098): getReservedSendMessageCount(): retMessageCount=0
E/PersonaManagerService(  922): inState():  stateMachine is null !!
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1181): value : false
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/Zygote  ( 7171): MountEmulatedStorage()
E/Zygote  ( 7171): v2
I/libpersona( 7171): KNOX_SDCARD checking this for 10024
I/libpersona( 7171): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7171 uid=10024 gids={50024, 9997} abi=armeabi-v7a
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  317): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 11.336ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.633ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
I/SELinux ( 7171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy(  922): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  922): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  922): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 258us total 8.059ms
W/ActivityManager(  922): mDVFSHelper.acquire()
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7171): TimaSignature is unavailable
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 7171): Added TimaKeyStore provider
D/SSRM:m  (  922): SIOP:: AP = 350, PST = 366, CUR = 450
E/Zygote  ( 7186): MountEmulatedStorage()
E/Zygote  ( 7186): v2
I/libpersona( 7186): KNOX_SDCARD checking this for 10356
I/libpersona( 7186): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7186 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/AndroidRuntime( 7135): Shutting down VM
I/SELinux ( 7186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7186): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7171): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
W/ResourcesManager( 7171): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7186): TimaSignature is unavailable
I/SystemBroadcastReceiver( 6242): [#DCM#] [DCM_Performance] onReceive completed in time  663 microsec. 
D/ActivityThread( 7186): Added TimaKeyStore provider
I/SystemBroadcastReceiver( 6242): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6242): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6242): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
W/ActivityManager(  922): getTasks: caller 10085 does not hold GET_TASKS; limiting output
W/ActivityManager(  922): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3477): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3477): getDatabaseLocked(b,b,pwd)...
D/PowerManagerService(  922): [PWL] sb release: PowerManagerService.Broadcasts
D/ResourcesManager( 7186): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
D/Mms/Omacp( 7098): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Mms/MmsApp( 7098): [end]    onCreate() consume time = 391.266042
D/Mms/PerformanceUtils( 7098): link cahcing start
V/AlarmManager(  922): waitForAlarm result :4
D/Mms/FreeMessageReceiver( 7098): onReceive, action : android.intent.action.PACKAGE_ADDED
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
D/Mms/DownloadManager( 7098): Service state changed: Bundle[mParcelledData.dataSize=692]
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  922): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  922): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  922): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  922): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/Mms/DownloadManager( 7098): roaming ------> false, mSimSlot = 0
D/Mms/TelephonyUtils( 7098): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager( 7098): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7098): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7098): auto download without roaming -> true
D/Mms/DownloadManager( 7098): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
I/QCOM PowerHAL(  922): Got set_interactive hint
D/Mms/DownloadManager( 7098): mAutoDownload ------> true
I/PowerManagerService(  922): [PWL] Off : 0s ago
I/PowerManagerService(  922): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  922): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  922): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=922, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=17)
I/PowerManagerService(  922): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  922): [PWL]     mDisplayReady : false
D/DisplayPowerController(  922): getFinalBrightness : 0 -> 0
D/PowerManagerService(  922): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  922): [PWL] sb release: PowerManagerService.Display
E/Zygote  ( 7203): MountEmulatedStorage()
E/Zygote  ( 7203): v2
I/libpersona( 7203): KNOX_SDCARD checking this for 10050
I/libpersona( 7203): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7203 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/ActivityManager(  922): Killing 5924:com.sec.android.widgetapp.digitalclock/u0a93 (adj 15): bgCount ##41
D/Mms/PerformanceUtils( 7098): link cahcing done
I/SELinux ( 7203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/WebViewFactory( 7186): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7186): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/SELinux ( 7203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  922): Killing 5939:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
I/LibraryLoader( 7186): Loading: webviewchromium
D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
I/LibraryLoader( 7186): Time to load native libraries: 5 ms (timestamps 6276-6281)
I/LibraryLoader( 7186): Expected native library version number "",actual native library version number ""
D/BatteryService(  922): stay LED for fully charged
D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/TimaKeyStoreProvider( 7203): TimaSignature is unavailable
D/ActivityThread( 7203): Added TimaKeyStore provider
D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/Mms/FreeMessageReceiverService( 7098): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3222): Disconnected process message: 10
W/libprocessgroup(  922): failed to open /acct/uid_10093/pid_5924/cgroup.procs: No such file or directory
D/Mms/FreeMessageReceiverService( 7098): onHandleIntent: ACTION_PACKAGE_ADDED
V/WebViewChromiumFactoryProvider( 7186): Binding Chromium to main looper Looper (main, tid 1) {233cd66e}
I/LibraryLoader( 7186): Expected native library version number "",actual native library version number ""
I/chromium( 7186): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  922): Killing 5634:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
I/BrowserStartupController( 7186): Initializing chromium process, renderers=0
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
D/ResourcesManager( 7203): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ResourcesManager( 7203): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7203): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/chromium( 7186): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7186): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7186): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7186): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7186): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7186): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7186): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7186): Remote Branch: 
I/Adreno-EGL( 7186): Local Patches: 
I/Adreno-EGL( 7186): Reconstruct Branch: 
W/libprocessgroup(  922): failed to open /acct/uid_10102/pid_5939/cgroup.procs: No such file or directory
W/libprocessgroup(  922): failed to open /acct/uid_10112/pid_5634/cgroup.procs: No such file or directory
D/MyFiles ( 7203): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager(  922): Killing 5959:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
W/chromium( 7186): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7186): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
E/installd(  298): system dir 0 : /system/app/
E/installd(  298): system dir 1 : /system/priv-app/
E/installd(  298): system dir 2 : /vendor/app/
E/installd(  298): system dir 3 : /oem/app/
I/TactileAssist(  922): enable value -1
I/TactileAssist(  922): internal enable value -1
I/TactileAssist(  922): intensity value -1
I/TactileAssist(  922): saveAppList value true
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
I/TactileAssist(  922): List of disabled apps :
W/AwContents( 7186): onDetachedFromWindow called when already detached. Ignoring
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/PackageManager(  922): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/libprocessgroup(  922): failed to open /acct/uid_10153/pid_5959/cgroup.procs: No such file or directory
E/Zygote  ( 7241): MountEmulatedStorage()
E/Zygote  ( 7241): v2
I/libpersona( 7241): KNOX_SDCARD checking this for 10057
I/libpersona( 7241): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7241 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 7241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/SystemWebViewEngine( 7186): CordovaWebView is running on device made by: samsung
E/SELinux ( 7241): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 7241): TimaSignature is unavailable
D/ActivityThread( 7241): Added TimaKeyStore provider
D/ResourcesManager( 7241): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7241): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 7241): onReceive() it will make start service
D/Compatibility( 7241): onHandleIntent()
D/Compatibility( 7241): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7241): found: 2
I/UpdateIcingCorporaServi( 1715): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7241): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7241): skipping ResolveInfo{36213a22 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7241): considering ResolveInfo{4284cb3 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7241): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7241): enabling receiver ResolveInfo{11f96270 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ContextImpl( 6010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7241): enabling receiver ResolveInfo{35cd39e9 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7241): enabling receiver ResolveInfo{233cd66e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7241): enabling receiver ResolveInfo{1151010f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7241): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/Activity( 7186): performCreate Call secproduct feature valuefalse
D/Activity( 7186): performCreate Call debug elastic valuetrue
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7265): MountEmulatedStorage()
E/Zygote  ( 7265): v2
I/libpersona( 7265): KNOX_SDCARD checking this for 10097
I/libpersona( 7265): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7265 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 1715): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/UpdateIcingCorporaServi( 1715): UpdateCorporaTask done [took 87 ms] updated apps [took 86 ms] 
I/SELinux ( 7265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/OpenGLRenderer( 7186): Render dirty regions requested: true
E/SELinux ( 7265): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager(  922): post active user change for 0
D/KnoxTimeoutHandler(  922): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  922): handleActiveUserChange for user 0
E/SMD     (  288): DCD ON
D/TimaKeyStoreProvider( 7265): TimaSignature is unavailable
D/ActivityThread( 7265): Added TimaKeyStore provider
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7265): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/OpenGLRenderer( 7186): Initialized EGL, version 1.4
I/OpenGLRenderer( 7186): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7186): Enabling debug mode 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputMethodManagerService(  922): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 7186): Timeline: Activity_idle id: android.os.BinderProxy@3a2b6f59 time:106714
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/IInputConnectionWrapper( 7186): showStatusIcon on inactive InputConnection
W/ActivityManager(  922): mDVFSHelper.release()
I/Timeline(  922): Timeline: Activity_windows_visible id: ActivityRecord{12dbac0 u0 com.test.thalitest/.MainActivity t4} time:106731
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/DocsApplication( 7265): Installing DEX configuration.
D/DexInstaller( 7265): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7265): Provided clientMode=RELEASE, packageInfo=PackageInfo{3682cbed com.google.android.apps.docs}
D/JsMessageQueue( 7186): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7186): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7186): 
D/TAG     ( 7265): onCreate()
D/CrossAppStateProvider( 7265): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/jxcore_app_log( 7186): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358144512
D/JX-Cordova( 7186): jxcore cordova android initializing
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7308): MountEmulatedStorage()
I/libpersona( 7308): KNOX_SDCARD checking this for 10098
E/Zygote  ( 7308): v2
I/libpersona( 7308): KNOX_SDCARD not a persona
W/GAV2    ( 7265): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  922): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7308 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
I/SELinux ( 7308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7308): TimaSignature is unavailable
D/ActivityThread( 7308): Added TimaKeyStore provider
D/ResourcesManager( 7308): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7308): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 7308): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7308): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7308): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7332): MountEmulatedStorage()
E/Zygote  ( 7332): v2
I/libpersona( 7332): KNOX_SDCARD checking this for 10032
I/libpersona( 7332): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7332 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7332): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7332): TimaSignature is unavailable
,D/ActivityThread( 7332): Added TimaKeyStore provider
,D/ResourcesManager( 7332): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7332): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 7265): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  922): Killing 5652:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,W/jxcore-log( 7186): Initializing JXcore engine
,W/jxcore-log( 7186): JXcore engine is ready
,I/System.out( 7332): Inside onCreate() of WakeupTriggerProvide
,W/jxcore-log( 7186): Starting JXcore engine
,I/System.out( 7332): Inside WakeupProvider
,E/DatabaseUtils( 7332): Writing exception to parcel
E/DatabaseUtils( 7332): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7332): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7332): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7332): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7332): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7332): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7332): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7332): 	at android.os.Binder.execTransact(Binder.java:446)
,W/libprocessgroup(  922): failed to open /acct/uid_10148/pid_5652/cgroup.procs: No such file or directory
,W/System.err( 7308): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,E/auditd  ( 2204): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  922): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  922): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/System.err( 7308): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7308): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7308): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7308): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7308): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7308): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
,W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7308): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7308): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7308): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7308): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
,W/System.err( 7308): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7308): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7308): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7308): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7308): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7308): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
,W/System.err( 7308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7308): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7308): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7308): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7308): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7308): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7308): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/VlingoApplication( 7332): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
,E/DatabaseUtils( 7332): Writing exception to parcel
E/DatabaseUtils( 7332): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7332): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7332): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7332): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7332): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7332): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7332): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7332): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7332): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7308): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7308): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7308): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7308): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7308): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7308): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7308): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7308): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7308): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7308): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7308): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7308): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7308): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7308): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7308): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7308): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7308): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7308): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7308): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7308): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7308): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7308): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7308): [DLApplication]-Init Called!:false
E/[CarMode]( 7308): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7308): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7308): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7308): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7308): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7308): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7308): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7308): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7308): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7308): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7308): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7308): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7308): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7308): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7308): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoAndroidCore( 7332): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 7308): initialize
D/[CarModeFW]( 7308): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7308): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7308): DrivingManager-initialize...
D/[CarModeFW]( 7308): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7308): CDH-ContactDataHandler initiazlieCaches time : 15
D/[CarModeFW]( 7308): CDH-initiazlieCaches : end sync
I/SensorService(  922): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  922): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  922): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,W/jxcore-log( 7186): Platform android
W/jxcore-log( 7186): 
W/jxcore-log( 7186): Process ARCH arm
W/jxcore-log( 7186): 
,D/VlingoApplication( 7332): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7332): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7308): Need to enable context aware info
,V/MediaPlayer-JNI( 7308): native_setup
V/MediaPlayer( 7308): constructor
,V/MediaPlayer( 7308): setListener
,E/MediaPlayer-JNI( 7308): QCMediaPlayer mediaplayer NOT present
,I/art     (  922): Explicit concurrent mark sweep GC freed 226951(15MB) AllocSpace objects, 5(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.431ms total 95.386ms
,D/[CarModeFW]( 7308): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7308): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 7308): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 7308): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450736130951
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450736130951
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450736130952
,D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450736130952
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450736130952
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450736130952
,I/[CarMode]( 7308): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/[CarMode]( 7308): [DLApplication]-Init End!:true
,D/[CarModeFW]( 7308): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/SmsProvider( 1464): query,matched:2, calling pid = 7308
,D/TP/SmsProvider( 1464): query,matched:2, calling pid = 7308
D/[CarModeFW]( 7308): RecommendHandler-selection = type = '3'
,D/TP/SmsProvider( 1464): match 2:Elapsed time : 1.315 ms
D/TP/SmsProvider( 1464): match 2:Elapsed time : 1.458 ms
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7371): MountEmulatedStorage()
E/Zygote  ( 7371): v2
I/libpersona( 7371): KNOX_SDCARD checking this for 10019
I/libpersona( 7371): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7371 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 7371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 7308):  getInboxList smsCursor : 65
I/SELinux ( 7371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarModeFW]( 7308): CDH-buildContactCacheWireFrame : cur len =0
E/SELinux ( 7371): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1464): Query uri=content://mms/inbox, match=2, calling pid = 7308
,D/[CarMode]( 7308): [DLApplication]-GooglePlayServices SUCCESS.
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7384): MountEmulatedStorage()
,E/Zygote  ( 7384): v2
I/libpersona( 7384): KNOX_SDCARD checking this for 10003
I/libpersona( 7384): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7384 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 7308): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7308): Intent : android.intent.action.PACKAGE_ADDEDMon Dec 21 23:15:31 GMT+01:00 2015
,I/SELinux ( 7384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 7308
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7371): TimaSignature is unavailable
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/SELinux ( 7384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 7371): Added TimaKeyStore provider
,I/ActivityManager(  922): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7399): MountEmulatedStorage()
,E/Zygote  ( 7399): v2
I/libpersona( 7399): KNOX_SDCARD checking this for 1000
I/libpersona( 7399): KNOX_SDCARD not a persona
,I/SELinux ( 7399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7384): TimaSignature is unavailable
,D/ActivityThread( 7384): Added TimaKeyStore provider
,D/MessageDataHandler( 7308):  getInboxList mmsCursor : 155
,I/MessageDataHandler( 7308): getUnreadMessageCount :0
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 234
,D/TimaKeyStoreProvider( 7399): TimaSignature is unavailable
,D/ActivityThread( 7399): Added TimaKeyStore provider
,I/ActivityManager(  922): Killing 5667:com.android.calendar/u0a149 (adj 15): bgCount ##41
,D/ResourcesManager( 7371): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarModeFW]( 7308): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7308): PushMessageService-onCreate
D/MessageDataHandler( 7308):  getInboxList mms,sms cursor join : 29
,D/[CarModeFW]( 7308): RecommendHandler-selection = type = '3'
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 7308
,V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 1.257 ms
D/ResourcesManager( 7399): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 7308
,D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 0.900 ms
,D/MessageDataHandler( 7308):  getInboxList address cursor : 5
,I/ActivityManager(  922): Killing 6158:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
,I/ActivityManager(  922): Killing 6116:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##42
,I/ActivityManager(  922): Killing 6101:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##43
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 7308
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 0.850 ms
,D/ResourcesManager( 7384): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/MessageDataHandler( 7308):  getInboxList thread cursor : 6
,D/MessageDataHandler( 7308):  thread, addr result: 2
,I/[CarModeFW]( 7308): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 270
I/[CarModeFW]( 7308): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 271
,W/ContextImpl( 7399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.PlaceProvider( 7384): PlaceProvider onCreate()
,E/Zygote  ( 7418): MountEmulatedStorage()
E/Zygote  ( 7418): v2
I/libpersona( 7418): KNOX_SDCARD checking this for 10111
I/libpersona( 7418): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7418 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/[CarModeFW]( 7308): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7308): PushMessageService-registerPushMessageServiceListener
,I/SELinux ( 7418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7399): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/TimaKeyStoreProvider( 7418): TimaSignature is unavailable
,D/ActivityThread( 7418): Added TimaKeyStore provider
D/UserAnalysis.SecureDbManager( 7384): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7384): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7384): Create SecureDbHelper
,D/ResourcesManager( 7418): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 7308): -[snowdeer] Rec : Missed Call : 400
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 408
,E/FilterInstaller( 7399): There is no requred permission
,D/IntelligenceServiceApplication( 7384): onCreate()
,I/ActivityManager(  922): Killing 6183:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 7384): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7384): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7384): Open Place.db in secure mode
,D/PackageIntentReceiver( 7418): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 7418): Not GearManger package! 
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7435): MountEmulatedStorage()
E/Zygote  ( 7435): v2
I/libpersona( 7435): KNOX_SDCARD checking this for 10117
I/libpersona( 7435): KNOX_SDCARD not a persona
,I/SQLiteSecureOpenHelper( 7384): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7384): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  922): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7435 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 6365:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/art     (  317): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 14.808ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.950ms
,I/jxcore-log( 7186): JXcore Cordova bridge is ready!
I/jxcore-log( 7186): 
W/jxcore-log( 7186): JXcore engine is started
,I/SELinux ( 7435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7435): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 258us total 9.580ms
,D/[CarModeFW]( 7308): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7308): MyPlaceProvider-=============
,D/[CarModeFW]( 7308): MyPlaceProvider-=============
D/[CarModeFW]( 7308): MyPlaceProvider-=============
D/[CarModeFW]( 7308): MyPlaceProvider-=============
D/[CarModeFW]( 7308): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7308): MyPlaceProvider-==============
D/[CarModeFW]( 7308): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7308): MyPlaceProvider-==============
D/[CarModeFW]( 7308): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7308): MyPlaceProvider-==============
D/[CarModeFW]( 7308): MyPlaceProvider-latitude is not valid
,I/[CarModeFW]( 7308): -[snowdeer] Rec : Favorite : 80
,D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 499
,D/[CarMode]( 7308): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@8f682943, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6a513f7d] LOCATIONS
,D/TimaKeyStoreProvider( 7435): TimaSignature is unavailable
I/[CarModeFW]( 7308): -[snowdeer] Rec : CallLog : 14
,D/ActivityThread( 7435): Added TimaKeyStore provider
,I/[CarModeFW]( 7308): -[snowdeer] Rec : Schedule : 14
,I/[CarModeFW]( 7308): -[snowdeer] Rec : During DL app : 1
,I/[CarModeFW]( 7308): -[snowdeer] Rec : Location Sharing : 1
,I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7308): -[snowdeer] Rec : POI : 0
,I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
D/ResourcesManager( 7435): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 524
I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 7308): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7308): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 524
,W/ResourcesManager( 7435): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_6101/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10035/pid_6116/cgroup.procs: No such file or directory
W/libprocessgroup(  922): failed to open /acct/uid_10037/pid_6158/cgroup.procs: No such file or directory
W/libprocessgroup(  922): failed to open /acct/uid_10149/pid_5667/cgroup.procs: No such file or directory
,D/MagazineService Version( 7435): Magazine-Administrator: 11
,D/MagazineService Version( 7435): Magazine-Provider: 14
,D/MagazineService Version( 7435): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7435): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7435): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7435): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7451): MountEmulatedStorage()
,E/Zygote  ( 7451): v2
I/libpersona( 7451): KNOX_SDCARD checking this for 1000
I/libpersona( 7451): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7451 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7435): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager(  922): Killing 5780:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,I/SELinux ( 7451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  922): failed to open /acct/uid_10037/pid_6183/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_6365/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7451): TimaSignature is unavailable
,D/ActivityThread( 7451): Added TimaKeyStore provider
,D/ResourcesManager( 7451): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  922): failed to open /acct/uid_10157/pid_5780/cgroup.procs: No such file or directory
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7466): MountEmulatedStorage()
E/Zygote  ( 7466): v2
I/libpersona( 7466): KNOX_SDCARD checking this for 1000
I/libpersona( 7466): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7466 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 4694:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/System.out( 7332): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7466): TimaSignature is unavailable
,D/ActivityThread( 7466): Added TimaKeyStore provider
,D/ResourcesManager( 7466): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  922): failed to open /acct/uid_10045/pid_4694/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7466): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7466): Enter Oncreate
,D/AcmsServiceMonitor( 7466): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7466): creating AcmsCore
,D/AcmsCore( 7466): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7466): AcmsCore
,D/AcmsCore( 7466): init
,D/AcmsCore( 7466): Looper handler is not null
D/AcmsCore( 7466): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7466): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7466): Incrementing - Counter value: 1
D/AcmsCore( 7466): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7466): onStartCommand
,D/AcmsCertificateMngr( 7466): AcmsCertificateMngr
D/AcmsService( 7466): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7466): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7466): Incrementing - Counter value: 2
D/AcmsService( 7466): Incremented Counter Value : onStartCommand
,D/AcmsRevocationMngr( 7466): AcmsRevocationMngr
,D/ActivityThread( 7466): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7466): Inside handle Intent
,D/AcmsService( 7466): App added - package name: com.test.thalitest
,D/AcmsCore( 7466): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7466): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7466): Incrementing - Counter value: 3
D/AcmsCore( 7466): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7466): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7466): Decrementing - Counter value: 2
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7486): MountEmulatedStorage()
E/Zygote  ( 7486): v2
I/libpersona( 7486): KNOX_SDCARD checking this for 10165
I/libpersona( 7486): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7486 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7486): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7486): TimaSignature is unavailable
,D/ActivityThread( 7486): Added TimaKeyStore provider
,D/ResourcesManager( 7486): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7486): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7486): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/SMD     (  288): DCD ON
,E/Zygote  ( 7501): MountEmulatedStorage()
I/libpersona( 7501): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7501): v2
I/libpersona( 7501): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7501 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 6028:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,I/SELinux ( 7501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7501): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7501): TimaSignature is unavailable
,D/ActivityThread( 7501): Added TimaKeyStore provider
,D/ResourcesManager( 7501): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7501): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup(  922): failed to open /acct/uid_10116/pid_6028/cgroup.procs: No such file or directory
,D/Finsky  ( 6527): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  922): Killing 6421:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2478): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2478): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2478): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  922): failed to open /acct/uid_10074/pid_6421/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2478): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2478): Submit a task: k
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2478): Processing package: com.test.thalitest
,W/BaseAppContext( 2478): Using Auth Proxy for data requests.
W/BaseAppContext( 2478): Using Auth Proxy for data requests.
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7525): MountEmulatedStorage()
I/libpersona( 7525): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7525): v2
I/libpersona( 7525): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7525 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/GassUtils( 2478): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2478): Found info for package com.test.thalitest in db.
,I/SELinux ( 7525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7525): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/PeopleDatabaseHelper( 2478): cleanUpNonGplusAccounts done.
,D/TimaKeyStoreProvider( 7525): TimaSignature is unavailable
,D/ActivityThread( 7525): Added TimaKeyStore provider
,D/ResourcesManager( 7525): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2478): Using Auth Proxy for data requests.
,I/jxcore-log( 7186): Toggling radios to true
I/jxcore-log( 7186): 
,W/BaseAppContext( 2478): Using Auth Proxy for data requests.
D/BluetoothAdapter( 7186): enable()
,D/BluetoothAdapter( 7186): enable(): BT is already enabled..!
,W/BaseAppContext( 2478): Using Auth Proxy for data requests.
W/BaseAppContext( 2478): Using Auth Proxy for data requests.
,D/WifiService(  922): New client listening to asynchronous messages
,I/WifiManager( 7186): packageName : com.test.thalitest
,D/SecContentProvider(  922): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  922): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  922): mCursor = null
,D/WifiService(  922): setWifiEnabled: true pid=7186, uid=10356
E/WifiService(  922): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  922): Permission Denial: getCurrentUser() from pid=7186, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  922): Failed getting userId using ActivityManagerNative
W/WifiService(  922): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7186, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  922): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  922): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  922): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  922): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  922): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  922): name = wifi_on
,W/BaseAppContext( 2478): Using Auth Proxy for data requests.
,I/WifiService(  922): disconnect: pid=7186, uid=10356
,I/jxcore-log( 7186): Radios toggled
I/jxcore-log( 7186): 
,I/wpa_supplicant( 1305): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7186): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): Perf Test app loaded loaded
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): check test folder
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): found test : ./testFindPeers.js
I/jxcore-log( 7186): 
,I/wpa_supplicant( 1305): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1305): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  922): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1305): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1305): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1305): Disconnected - do not scan
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  922): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  922): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  922): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7186): found test : ./testSendData.js
I/jxcore-log( 7186): 
,E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  922): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  922): do suspend true
,D/WifiP2pService(  922): InactiveState{ what=143375 }
,D/WifiP2pService(  922): P2pEnabledState{ what=143375 }
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2272): Read error: ssl=0x9b7cbe00: I/O error during system call, Connection timed out
,I/jxcore-log( 7186): found test : ./testSendData2.js
I/jxcore-log( 7186): 
,V/NativeCrypto( 2272): SSL shutdown failed: ssl=0x9b7cbe00: I/O error during system call, Broken pipe
,E/jxcore  ( 7186): Error!: missing ) after argument list
E/jxcore  ( 7186): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
D/ConnectivityService(  922): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,I/chromium( 7186): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,E/WifiStateMachine(  922): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  922): updateNetworkInfo()
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  922): updateNetworkInfo()
I/WifiTrafficPoller(  922): evaluateTrafficStatsPolling
D/ConnectivityService(  922): ignoring duplicate network state non-change
,I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524290
,E/WifiStateMachine(  922): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/wpa_supplicant( 1305): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1305): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1305): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1305): First Scan Start
,I/wpa_supplicant( 1305): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  922): ConnectModeState: Network connection lost 
E/WifiStateMachine(  922): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  922): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  922): do suspend true
,D/WifiP2pService(  922): InactiveState{ what=143375 }
D/WifiP2pService(  922): P2pEnabledState{ what=143375 }
,I/ActivityManager(  922): Killing 6443:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7547): MountEmulatedStorage()
I/libpersona( 7547): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7547): v2
I/libpersona( 7547): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/ConnectivityService(  922): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  922): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  922): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  922): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  922): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Disconnected - quitting
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiStateMachine(  922): updateConfiguredNetworkExpiration - currTime: 1450736132783
D/WifiStateMachine(  922): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
I/WifiTrafficPoller(  922): evaluateTrafficStatsPolling
E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  922): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  922): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker(  922): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  922): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  922): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  922): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  922): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/SmartBondingService(  922): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,E/WifiStateMachine(  922): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/WifiNetworkAgent(  922): NetworkAgent: NetworkAgent channel lost
V/NetworkStats(  922): updateIfacesLocked()
V/NetworkStats(  922): performPollLocked(flags=0x1)
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  922): UpdateStatsForKnox
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  922): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  922): mCursor = null
V/NetworkStats(  922): performPollLocked() took 8ms
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  922): mCursor = null
,I/SELinux ( 7547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
I/SELinux ( 7547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/SmartBondingService(  922): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
V/NetworkStats(  922): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1464): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TimaKeyStoreProvider( 7547): TimaSignature is unavailable
,D/ActivityThread( 7547): Added TimaKeyStore provider
,I/chromium( 7186): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_6443/cgroup.procs: No such file or directory
,D/ResourcesManager( 7547): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/SecurityLogAgent( 7547):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/SecurityLogAgent( 7547):  SeDenialReceiver : File path = null
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
I/ActivityManager(  922): Killing 6485:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/BootupListener( 1464): ACTION_DRIVELINK
,D/SettingsProvider(  922): name = drivelink_navigation
,D/SettingsProvider(  922): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  922): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  922): selectionArgs: false
D/SettingsProvider(  922): selectionArgs: 1001
,D/SecContentProvider(  922): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  922): ret = -1
D/BootupListener( 1464): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  922): name = internet_call_settings_visibility
D/SettingsProvider(  922): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  922): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  922): selectionArgs: false
D/SettingsProvider(  922): selectionArgs: 1001
D/SecContentProvider(  922): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  922): ret = -1
,I/Hs20UtilService( 1315): Starting #6
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1315): Starting #7
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_6485/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 7466):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7466): Key Store exist
I/AcmsKeyStoreHelper( 7466): Hence loading the keystore file
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,D/AcmsKeyStoreHelper( 7466):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 7466): getKeyStoreForApplication success 
D/AcmsCore( 7466): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7466): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7466): Decrementing - Counter value: 1
D/AcmsCore( 7466): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7466): This is NOT a valid MirrorLink app
D/AcmsCore( 7466): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7466): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7466): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 7466): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7466): getSvcCounter - Counter value: 0
D/AcmsService( 7466): Enter onDestroy
I/AcmsService( 7466): cleanUp(): inside service clean up
D/AcmsCore( 7466): AcmsCore: inside DeInit
D/AcmsCore( 7466): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7466): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7466): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7466): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7466): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7466): getSvcCounter - Counter value: 0
D/AcmsService( 7466): killing acms process
I/Process ( 7466): Sending signal. PID: 7466 SIG: 9
,W/art     ( 2478): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 139.510ms
,I/ActivityManager(  922): Process ACMS.Process (pid 7466)(adj 0) has died(81,548)
,D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  922): updateDataUsageMap
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  922): MasterInitialState.processMessage what=3
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  922): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1941): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  922): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
,D/SmartBondingService(  922): getSBEnabled() enabled =false
,I/CLocInfoService(  922): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  922): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  922): CLoinfo wifi false
,I/SystemBroadcastReceiver( 6242): [#DCM#] [DCM_Performance] onReceive completed in time  2384 microsec. 
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  922): No Active Data Connection
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6202): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 7038): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7038): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7038): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7038): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7038): noConnectivity : true
,I/SystemBroadcastReceiver( 6242): [#DCM#] Calling notifyListeners. 
,I/DCMController( 6242): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 6242): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7587): MountEmulatedStorage()
I/libpersona( 7587): KNOX_SDCARD checking this for 10002
E/Zygote  ( 7587): v2
I/libpersona( 7587): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3684): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/ActivityManager(  922): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7587 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3684): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7587): TimaSignature is unavailable
,D/ActivityThread( 7587): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 2478): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2478): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 7587): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  922): waitForAlarm result :4
,I/ActivityManager(  922): Killing 5762:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7612): MountEmulatedStorage()
,E/Zygote  ( 7612): v2
I/libpersona( 7612): KNOX_SDCARD checking this for 1000
I/libpersona( 7612): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7612 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7612): TimaSignature is unavailable
,D/ActivityThread( 7612): Added TimaKeyStore provider
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_5762/cgroup.procs: No such file or directory
,D/ResourcesManager( 7612): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/Icing   ( 2478): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7612): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ResourcesManager( 2478): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/Icing   ( 2478): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,I/PowerManagerService(  922): [PWL] Off : 5s ago
,I/PowerManagerService(  922): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  922): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  922): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2797)
I/PowerManagerService(  922): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2697)
I/PowerManagerService(  922): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=922, ws=null) (elapsedTime=845)
I/PowerManagerService(  922): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=922, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=190)
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7628): MountEmulatedStorage()
E/Zygote  ( 7628): v2
I/libpersona( 7628): KNOX_SDCARD checking this for 10010
I/libpersona( 7628): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7628 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7628): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7628): TimaSignature is unavailable
,D/ActivityThread( 7628): Added TimaKeyStore provider
,D/ResourcesManager( 7628): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1305): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1305): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1305): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1305): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  922): [1,450,736,133,809 ms] noteScanEnd no scan source
,E/WifiStateMachine(  922): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@5c740d5 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  922): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  922): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info0x
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  922): mCursor = null
,I/ActivityManager(  922): Killing 5992:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,I/FOTA_Client( 7628): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7628): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7628): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7643): MountEmulatedStorage()
E/Zygote  ( 7643): v2
I/libpersona( 7643): KNOX_SDCARD checking this for 10018
I/libpersona( 7643): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7643 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 5837:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,I/wpa_supplicant( 1305): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1305): Associated with C0.AA.48
,E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  922): mCursor = null
,I/wpa_supplicant( 1305): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  922): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  922): mCursor = null
,I/SELinux ( 7643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  922): failed to open /acct/uid_10167/pid_5992/cgroup.procs: No such file or directory
,I/SELinux ( 7643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1305): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1305): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1305): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1305): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1305): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1305): Blacklist: Clear (temp) 
I/wpa_supplicant( 1305): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  922): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  922): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,W/libprocessgroup(  922): failed to open /acct/uid_10113/pid_5837/cgroup.procs: No such file or directory
,E/WifiStateMachine(  922): Network connection established
,D/WifiNative-HAL(  922): callSECApiVoid - ID [50]
,E/WifiStateMachine(  922): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  922): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/FactoryTest( 6579): Not factory mode
D/FactoryTest( 6579): Not factory mode. isFactoryMode() returend false
,I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  922): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  922): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  922): Got NetworkAgent Messenger
D/ConnectivityService(  922): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  922): updateNetworkInfo()
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922): NetworkAgent connected
,E/WifiStateMachine(  922): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/MTPRx   ( 6579): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6579): still no open session command from host, so toast
,W/ContextImpl( 6579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6579): Timeline: Activity_launch_request id:com.android.settings time:111525
E/PersonaManagerService(  922): inState():  stateMachine is null !!
,V/ApplicationPolicy(  922): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  922): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  922): mDVFSHelper.acquire()
,D/TimaKeyStoreProvider( 7643): TimaSignature is unavailable
D/ActivityThread( 7643): Added TimaKeyStore provider
E/WifiStateMachine(  922): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  922): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  922): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  922): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/MTPRx   ( 6579): started activity for popup
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  282): Setting iface cfg
,E/WifiStateMachine(  922): Start Dhcp Watchdog 2
,D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  922): mCursor = null
,I/SQLiteSecureOpenHelper( 3477): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3477): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 7643): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7643): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7643): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736134000
,I/KLMS-2.4.503: ( 7643): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7643): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7643): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  922): Killing 6242:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/ResourcesManager( 6579): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6579): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6579): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6579): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6579): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7666): MountEmulatedStorage()
E/Zygote  ( 7666): v2
I/libpersona( 7666): KNOX_SDCARD checking this for 10036
I/libpersona( 7666): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7666 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 299us total 15.547ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.656ms
,E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  922): do suspend false
,D/WifiP2pService(  922): InactiveState{ what=143375 }
D/SecContentProvider2(  922): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  922): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  922): mCursor = null
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 259us total 8.213ms
,I/SELinux ( 7666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7666): TimaSignature is unavailable
,E/SettingsReceiverActivity( 6579): PREF_DONT_ASK_AGAIN : true
D/ActivityThread( 7666): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,W/libprocessgroup(  922): failed to open /acct/uid_10004/pid_6242/cgroup.procs: No such file or directory
,D/InputMethodManagerService(  922): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  922): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@201f4372 attribute=null, token = android.os.BinderProxy@2d7222d9
,D/ResourcesManager( 7666): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/SO_AGENT( 7666): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6579): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/SPPClientService( 5149): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SettingsReceiverActivity( 6579): dev.kiessupport is : TRUE
,I/SA      ( 7075): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7075): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7075): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7075): [SLFUCHKMGR] constructor called
,I/SA      ( 7075): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7075): [OR] == isSIMCardReady false ==
I/SA      ( 7075): [SCU] == networkStateCheck == false
I/SA      ( 7075): [OR] onReceive END
,D/Activity( 6579): performCreate Call secproduct feature valuefalse
D/Activity( 6579): performCreate Call debug elastic valuetrue
,E/SPPClientService( 5149): [[SystemStateMonitorService]] No Active Internet
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7684): MountEmulatedStorage()
I/libpersona( 7684): KNOX_SDCARD checking this for 10070
E/Zygote  ( 7684): v2
I/libpersona( 7684): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7684 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActivityManager(  922): post active user change for 0
D/KnoxTimeoutHandler(  922): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  922): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/SELinux ( 7684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  922): Killing 6305:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/Timeline( 7186): Timeline: Activity_idle id: android.os.BinderProxy@3a2b6f59 time:111798
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/TimaKeyStoreProvider( 7684): TimaSignature is unavailable
,D/ActivityThread( 7684): Added TimaKeyStore provider
,W/libprocessgroup(  922): failed to open /acct/uid_10043/pid_6305/cgroup.procs: No such file or directory
D/ResourcesManager( 7684): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7684): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7684): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7684): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
,E/dhcpcd  ( 7703): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7684): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7684): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
,I/dhcpcd  ( 7703): version 5.5.6 starting
,D/SettingsProvider(  922): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  922): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  922): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  922): selectionArgs: false
D/SettingsProvider(  922): selectionArgs: 10070
D/SecContentProvider(  922): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  922): ret = -1
,E/dhcpcd  ( 7703): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7684): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7684): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7684): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7684): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7703): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7703): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7703): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7703): bssid match
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7703): wlan0: rebinding lease of 192.168.1.136
,E/Zygote  ( 7712): MountEmulatedStorage()
E/Zygote  ( 7712): v2
I/libpersona( 7712): KNOX_SDCARD checking this for 1000
I/libpersona( 7712): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 6722:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/SELinux ( 7712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7712): TimaSignature is unavailable
,D/ActivityThread( 7712): Added TimaKeyStore provider
,D/ResourcesManager( 7712): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/libprocessgroup(  922): failed to open /acct/uid_10011/pid_6722/cgroup.procs: No such file or directory
,W/ResourcesManager( 7712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7712): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7712): premStatus:2
,I/KnoxUsageLogPro( 7712): isEulaShown : false
I/KnoxUsageLogPro( 7712): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7727): MountEmulatedStorage()
,E/Zygote  ( 7727): v2
I/libpersona( 7727): KNOX_SDCARD checking this for 10087
I/libpersona( 7727): KNOX_SDCARD not a persona
,I/SELinux ( 7727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  922): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7727 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  922): Killing 7004:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,E/SELinux ( 7727): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7727): TimaSignature is unavailable
,D/ActivityThread( 7727): Added TimaKeyStore provider
,D/ResourcesManager( 7727): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  922): failed to open /acct/uid_10014/pid_7004/cgroup.procs: No such file or directory
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  922): Killing 7023:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,D/Headlines( 5377): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5377): getCountryCode(): countryCode = PL
,D/Headlines( 5377): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5377): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/HeadlinesCardManager( 5377): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5377): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7743): MountEmulatedStorage()
,E/Zygote  ( 7743): v2
I/libpersona( 7743): KNOX_SDCARD checking this for 10127
I/libpersona( 7743): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7743 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7743): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  922): failed to open /acct/uid_10015/pid_7023/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7743): TimaSignature is unavailable
,D/ActivityThread( 7743): Added TimaKeyStore provider
,D/ResourcesManager( 7743): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  ( 7703): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7703): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7743): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7743): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7743): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7743): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine(  922): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  922): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  922): do suspend true
,D/WifiP2pService(  922): InactiveState{ what=143375 }
,D/WifiP2pService(  922): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  922): WifiStateMachine DHCP successful
,E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  922): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  922): Not connected state, yet.
E/WifiStateMachine(  922): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  922): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  922): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  922): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  922): callSECApiInt - ID [210]
,E/WifiStateMachine(  922): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  922): updateNetworkInfo()
,I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  922): updateDnsLinkProperty: enter
,D/ConnectivityService(  922): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  922): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine.DnsPinger(  922): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  922): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  922): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  922): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  922): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  922): Now, connected state.
E/WifiStateMachine(  922): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  922): evaluateTrafficStatsPolling
,I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  922): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  922): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  922): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  922): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  922): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  922): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  922): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  282): QcRouteController
,I/WifiTrafficPoller(  922): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  922): mBoosterFLAG : 0
I/WifiTrafficPoller(  922): current booster mode : FullMode
,D/WifiNative-HAL(  922): callSECApiVoid - ID [212]
,I/CLocInfoService(  922): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  922): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  922): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  922): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/WebViewFactory( 7743): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7743): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7743): Loading: webviewchromium
,V/        (  282): QcRouteController
,I/LibraryLoader( 7743): Time to load native libraries: 5 ms (timestamps 2555-2560)
,I/LibraryLoader( 7743): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7743): Binding Chromium to main looper Looper (main, tid 1) {3f9cde5c}
,I/LibraryLoader( 7743): Expected native library version number "",actual native library version number ""
,I/chromium( 7743): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/BrowserStartupController( 7743): Initializing chromium process, renderers=0
,W/art     ( 7743): Attempt to remove local handle scope entry from IRT, ignoring
,V/        (  282): QcRouteController
,W/AudioManagerAndroid( 7743): Requires BLUETOOTH permission
,W/chromium( 7743): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7743): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7743): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/ConnectivityService(  922): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  922): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  922): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
E/ConnectivityService(  922): updateNetworkInfo()
D/ConnectivityService(  922): ignoring duplicate network state non-change
E/ConnectivityService(  922): updateNetworkInfo()
D/ConnectivityService(  922): ignoring duplicate network state non-change
D/ConnectivityService(  922): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Connected
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  922): Validated
,D/ConnectivityService(  922): currentScore = 0, newScore = 60
D/ConnectivityService(  922):    accepting network in place of null
D/ConnectivityService(  922): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1464): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SMD     (  288): DCD ON
,E/CSLegacyTypeTracker(  922): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  922): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  922): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  922): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Adreno-EGL( 7743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7743): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7743): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7743): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7743): Remote Branch: 
I/Adreno-EGL( 7743): Local Patches: 
I/Adreno-EGL( 7743): Reconstruct Branch: 
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524290
D/ConnectivityService(  922): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  922): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/SmartBondingService(  922): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  922): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/SmartBondingService(  922): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524290
,D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
V/NetworkStats(  922): updateIfacesLocked()
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
V/NetworkStats(  922): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  922): UpdateStatsForKnox
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  922): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
V/NetworkStats(  922): performPollLocked() took 4ms
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
V/NetworkStats(  922): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/NtpTrustedTime(  922): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/NSApplication( 7743): Starting up...
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/art     (  922): Explicit concurrent mark sweep GC freed 65517(3MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 35MB/51MB, paused 1.372ms total 89.628ms
,I/GAV2    ( 7265): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7841): MountEmulatedStorage()
E/Zygote  ( 7841): v2
I/libpersona( 7841): KNOX_SDCARD checking this for 10137
I/libpersona( 7841): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7841 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 6391:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  922): failed to open /acct/uid_10033/pid_6391/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7841): TimaSignature is unavailable
,D/ActivityThread( 7841): Added TimaKeyStore provider
,D/ResourcesManager( 7841): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7841): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7841): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7841): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7841): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7841): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7857): MountEmulatedStorage()
,E/Zygote  ( 7857): v2
I/libpersona( 7857): KNOX_SDCARD checking this for 10162
I/libpersona( 7857): KNOX_SDCARD not a persona
,I/ActivityManager(  922): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7857 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  922): Killing 4787:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7857): TimaSignature is unavailable
,D/ActivityThread( 7857): Added TimaKeyStore provider
,D/ResourcesManager( 7857): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7857): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup(  922): failed to open /acct/uid_10034/pid_4787/cgroup.procs: No such file or directory
W/ResourcesManager( 7857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7857): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7857): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/BadgeProvider( 7143): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  922): exchangeData() failure , invalid userId
D/ConnectivityService(  922): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/Launcher.Model( 1482): reloadBadges entered.
,D/BadgeProvider( 7143): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7143): sendNotify, [notify] : null
D/BadgeProvider( 7143): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7143): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7143): update, [UpdateCount] : 1
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  922): MasterInitialState.processMessage what=3
,D/SmartBondingService(  922): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  922): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  922): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  922): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  922): CLocinfo wifi true 
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  922): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  922): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1941): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2247): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3684): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3684): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6202): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7547): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7547): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7547): StateMachine : Current State = 1
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7547): StateMachine : Changed Current State = 1
,D/SecContentProvider2(  922): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  922): mCursor = null
I/ActivityManager(  922): Killing 5905:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7894): MountEmulatedStorage()
,E/Zygote  ( 7894): v2
I/libpersona( 7894): KNOX_SDCARD checking this for 10177
I/libpersona( 7894): KNOX_SDCARD not a persona
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,I/ActivityManager(  922): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7894 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/SELinux ( 7894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  922): failed to open /acct/uid_10041/pid_5905/cgroup.procs: No such file or directory
E/SELinux ( 7894): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/TimaKeyStoreProvider( 7894): TimaSignature is unavailable
,D/ActivityThread( 7894): Added TimaKeyStore provider
,D/ResourcesManager( 7894): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7857): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2272): Vacuum at: now=1450736135762 tag=VacuumService
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  922): Killing 5877:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7525): notifyNetworkActivated
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 7525): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  922): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  922): failed to open /acct/uid_10047/pid_5877/cgroup.procs: No such file or directory
,W/ActivityManager(  922): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7525): exit::IDLE
D/InitializeManagerStateMachine( 7525): entry::NETWORK_CHECK
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1315): Starting #8
I/Hs20UtilService( 1315): Message received 5007
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7525): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7525): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): entry::SUCCESS
D/hcjo    ( 7525): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7525): exit::SUCCESS
D/InitializeManagerStateMachine( 7525): entry::IDLE
,I/Hs20UtilService( 1315): Starting #9
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1315): Starting #10
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1315): Starting #11
,I/Hs20UtilService( 1315): Message received 5007
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  922): callSECApi what=220
D/WifiStateMachine(  922): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7038): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7038): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7038): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7038): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  922): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/PowerManagerService(  922): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=922
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/FOTA_Client( 7628): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7628): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7628): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/KLMS-2.4.503: ( 7643): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 7643): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736136106
I/KLMS-2.4.503: ( 7643): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7643): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7643): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7643): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/KLMS-2.4.503: ( 7643): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7666): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5149): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7075): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7075): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7075): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7075): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7075): [OR] == isSIMCardReady false ==
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7075): [SCU] == networkStateCheck == true
,I/SA      ( 7075): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7075): isChinaCountryCode : false
I/SA      ( 7075): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7075): [OR] == networkStateCheck true ==
,I/SA      ( 7075): [OR] GetMyCountryZoneTask
,I/SA      ( 7075): [OR] onReceive END
I/SA      ( 7075): [SRS] prepareGetMyCountryZone
,E/WifiStateMachine(  922): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  922): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  922): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  922): identical MTU - not setting
D/ConnectivityService(  922): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  922): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  282): QcRouteController
D/SmartBondingService(  922): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  922): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
D/SmartBondingService(  922): getSBEnabled() enabled =false
,I/SA      ( 7075): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/accuweather( 7684): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7075): [SSP] query invoked
D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,V/        (  282): QcRouteController
,I/KnoxUsageLogPro( 7712): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7712): premStatus:2
,I/KnoxUsageLogPro( 7712): isEulaShown : false
I/KnoxUsageLogPro( 7712): KnoxUsageReceiver onReceive : not Processible, just return
,W/NetworkManagementService(  922): route cmd failed: 
W/NetworkManagementService(  922): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  922): '
W/NetworkManagementService(  922): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  922): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  922): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  922): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  922): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  922): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  922): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  922): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  922): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  922): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  922): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  922): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService(  922): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  922): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  922): calling update connectivity
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  922): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
I/SA      ( 7075): [TPMU] GetMccFromDB : null
I/SA      ( 7075): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7075): [TPM] isNoProxy(default) : true
D/ConnectivityService(  922):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  922): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2478): CM callback handler got msg 524295
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Headlines( 5377): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5377): getCountryCode(): countryCode = PL
D/Headlines( 5377): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5377): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5377): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5377): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5377): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7075): fail readDirectory() errno=2
,D/QuickConnect( 7841): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7841): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7841): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  922): exchangeData() failure , invalid userId
D/RCPManagerService(  922): exchangeData() failure , invalid userId
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7547): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7547): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7547): StateMachine : Current State = 1
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7547): StateMachine : Changed Current State = 1
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7525): exit::IDLE
D/InitializeManagerStateMachine( 7525): entry::NETWORK_CHECK
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7525): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 7525): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7525): entry::SUCCESS
D/hcjo    ( 7525): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7525): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7525): exit::SUCCESS
D/InitializeManagerStateMachine( 7525): entry::IDLE
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2272): Scheduling Phenotype for one-off execution 3238 seconds from now (1450736136401)
,I/GCM     ( 2478): Message from null null
E/GCM     ( 2478): Dropping message from null
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GetConfigurationSnapshotOperation( 2272): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2272): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2272): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2272): Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10011, pid: 2272, getuid(): 10011
,I/qtaguid ( 2272): Tagging socket 89 with tag 1000040100000000{268436481,0} uid 10011, pid: 2272, getuid(): 10011
,I/SA      ( 7075): [RC New] Execute method=[GET] start
,I/SA      ( 7075): [RC New] Security=[true]
,I/System.out( 7075): Thread-1095(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7075): Thread-1095(ApacheHTTPLog):isShipBuild true
,I/System.out( 7075): Thread-1095(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,W/ActivityManager(  922): mDVFSHelper.release()
,I/qtaguid ( 2272): Tagging socket 93 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,D/LocationManagerService(  922): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7075): [RC New] [v2liruge] api execute + 589
,I/SA      ( 7075): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7075): AsyncTask #1 calls detatch()
,I/SA      ( 7075): [ODM] saveOpenData( GEO_IP, PL )
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2272): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 2272, getuid(): 10011
,I/SA      ( 7075): [OCP] update openData : PL
,I/SA      ( 7075): [TPMU] getNetworkMcc : 
,I/SA      ( 7075): [SCU] saveMccToPreferece Start
,I/SA      ( 7075): [SCU] RegionMCC : 260
I/SA      ( 7075): [SSP] query invoked
,I/SA      ( 7075): [TPMU] GetMccFromDB : null
,I/SA      ( 7075): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7075): [SCU] saveMccToPreferece End
I/SA      ( 7075): [RC New] executeRequest [v2liruge] end. 643
,I/SA      ( 7075): [RC New] Execute end
I/SA      ( 7075): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7075): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7186): BLE supported!!
I/jxcore-log( 7186): 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  922): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  922): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7703): wlan0: sending IPv6 Router Solicitation
,D/SSRM:m  (  922): SIOP:: AP = 400, PST = 362, CUR = 450
,D/PackageManager(  922): [MSG] MCS_UNBIND
,I/ActivityManager(  922): Killing 7171:com.wsomacp/u0a24 (adj 15): bgCount ##41
,W/libprocessgroup(  922): failed to open /acct/uid_10024/pid_7171/cgroup.procs: No such file or directory
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  922): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 922) eventTime = 117125
,D/PowerManagerService(  922): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=922 (0x0)
,D/PowerManagerService(  922): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=922, ws=WorkSource{10058}) (elapsedTime=3497)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/GAV4    ( 7743): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7038): mConnectivityHandler : connected
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7038): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7038): [GetString-S]
,I/ReactiveServiceManager( 7038): Supported : 1
,D/QSEECOMAPI: (  922): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  922): App is not loaded in QSEE
,D/QSEECOMAPI: (  922): Loaded image: APP id = 3
,D/QSEECOMAPI: (  922): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  922): QSEECom_shutdown_app, app_id = 3
E/terrier (  922): handleString: Failed to handle string(-4)
E/terrier (  922): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7038): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7038): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7038): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7038): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7038): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7038): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7703): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  922): [PWL] Off : 15s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7525): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7525): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7525): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7525): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7525): RestApi Request Add : 2307
,E/File    ( 7525): fail readDirectory() errno=2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7703): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7703): wlan0: no IPv6 Routers available
,I/System.out( 7525): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
D/PreloadUpdateManagerStateMachine( 7525): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/System.out( 7525): (HTTPLog)-Static: isShipBuild true
I/System.out( 7525): (HTTPLog)-Thread-1191-850453507: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7525): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7525, getuid(): 10039
,E/SMD     (  288): DCD ON
,I/qtaguid ( 7525): Untagging socket 26
,D/hcjo    ( 7525): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7525): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7525): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7525): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7525): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7525): RestApi Request Add : 2315
,V/AlarmManager(  922): waitForAlarm result :4
,I/qtaguid ( 7525): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7525, getuid(): 10039
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): stay LED for fully charged
D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 6527): [1065] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6527): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/qtaguid ( 7525): Untagging socket -1
,I/qtaguid ( 7525): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 7525): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7525): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7525): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 7525): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 7525): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 7525): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7525): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7525): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 7525): entry::IDLE
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 340, PST = 352, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 4
,V/AlarmManager(  922): waitForAlarm result :4
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  922): SIOP:: AP = 320, PST = 343, CUR = 450
,I/PowerManagerService(  922): [PWL] Off : 30s ago
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 300, PST = 337, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 50s ago
,D/SSRM:m  (  922): SIOP:: AP = 300, PST = 333, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 5
,D/SSRM:m  (  922): SIOP:: AP = 290, PST = 328, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 290, PST = 324, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 75s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 290, PST = 321, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 6
,I/ClearcutLoggerApiImpl( 2272): disconnect managed GoogleApiClient
,D/SSRM:m  (  922): SIOP:: AP = 290, PST = 317, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 290, PST = 311, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  922): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 270, PST = 298, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 7
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 270, PST = 291, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 270, PST = 286, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 140s ago
,D/SSRM:m  (  922): SIOP:: AP = 270, PST = 283, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 279, CUR = 450
,V/AlarmManager(  922): waitForAlarm result :8
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 276, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 273, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 9
,I/PowerManagerService(  922): [PWL] Off : 180s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 270, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 267, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 264, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  922): initializing...
,I/TLC_TIMA_PKM_initialize(  922): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  922): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  922): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  922): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  922): aligned max_sendmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  922): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  922): max_message_size = 524416 = 0x80080,
,D/QSEECOMAPI: (  922): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  922): App is not loaded in QSEE
,D/QSEECOMAPI: (  922): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  922): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  922): Trustlet response is completed
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 263, CUR = 450
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 262, CUR = 450
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  922): waitForAlarm result :4
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0,
,I/PowerManagerService(  922): [PWL] Off : 225s ago
,I/PowerManagerService(  922): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  922): [PWL]     mWakeLockSummary : 0x1
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
,I/ActivityManager(  922): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8005 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 8005): MountEmulatedStorage()
,E/Zygote  ( 8005): v2
I/libpersona( 8005): KNOX_SDCARD checking this for 10080
I/libpersona( 8005): KNOX_SDCARD not a persona
,I/SELinux ( 8005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,E/SELinux ( 8005): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8005): TimaSignature is unavailable
,D/ActivityThread( 8005): Added TimaKeyStore provider
,D/ResourcesManager( 8005): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  922): Killing 7098:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  922): No listener is left
,W/libprocessgroup(  922): failed to open /acct/uid_10049/pid_7098/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 11
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 12
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  922): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 275s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 13
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 14
,I/PowerManagerService(  922): [PWL] Off : 330s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 15
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/bootchecker(  323): bootchecker wake up!!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 16
,I/PowerManagerService(  922): [PWL] Off : 390s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): stay LED for fully charged
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 17
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 18
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 455s ago
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/art     ( 6500): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AclDataUtils( 6500): Circle ID not found for type: 9
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,I/Atfwd_Daemon(  328): Stop the daemon....
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 19
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :4
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 20
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  922): [PWL] Off : 525s ago
,E/SMD     (  288): DCD ON
,I/ActivityManager(  922): Killing 7203:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/libprocessgroup(  922): failed to open /acct/uid_10050/pid_7203/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 21
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 22
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  922): stay LED for fully charged
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 23
,I/PowerManagerService(  922): [PWL] Off : 600s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 24
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 25
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 680s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 26
,V/AlarmManager(  922): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/LightsService(  922): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  922): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
,D/SensorManager(  922): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  922): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  922): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  922): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  922): unregisterListener ::   
,D/LightsService(  922): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 27
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 28
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  922): [PWL] Off : 765s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 29
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 31
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  922): [PWL] Off : 855s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 32
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): stay LED for fully charged
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 33
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 34
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 950s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 35
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 36
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 37
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 38
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  922): stay LED for fully charged
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  922): [PWL] Off : 1050s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  922): stay LED for fully charged
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 39
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,I/UsageStatsService(  922): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  922): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  922): Updating Usage Statistics in DB @ 1450737234368
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61),
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
,W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  922): ::getAppControlDB: Exception to create DB
W/System.err(  922): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  922): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  922): Done Updating Usage Statistics in DB @ 1450737234585
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  922): Background sticky concurrent mark sweep GC freed 109678(10MB) AllocSpace objects, 339(5MB) LOS objects, 18% free, 36MB/44MB, paused 1.630ms total 132.735ms
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  922): !@Sync 41
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  922): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 42
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 43
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 44
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 45
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 1265s ago
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 46
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 47
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 48
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): stay LED for fully charged
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 49
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 1380s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 50
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/LightsService(  922): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  922): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  922): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2478): Aggregate from 1450735693629 (log), 1450735693629 (data)
,E/LightSensor(  922): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  922): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  922): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  922): unregisterListener ::   
D/LightsService(  922): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 51
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 52
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 53
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 54
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 55
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 56
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 57
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  922): [PWL] Off : 1625s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 58
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 59
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/NetworkStatsFactory(  922): UpdateStatsForKnox
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryService(  922): stay LED for fully charged
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/TimaService(  922): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  922): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  922): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 60
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  922): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  922): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,D/BatteryService(  922): stay LED for fully charged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  922): waitForAlarm result :8
,V/NetworkStats(  922): performPollLocked(flags=0x3)
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/NetworkStatsFactory(  922): UpdateStatsForKnox
,D/ConnectivityService(  922): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  922): performPollLocked() took 61ms
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,I/ProcessStatsService(  922): Prepared write state in 12ms
,E/SMD     (  288): DCD ON
,I/ProcessStatsService(  922): Prepared write state in 10ms
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/NtpTrustedTime(  922): currentTimeMillis() cache hit
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2272): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2272): SSL shutdown failed: ssl=0xaf51b800: I/O error during system call, Connection timed out
,V/NativeCrypto( 2272): SSL shutdown failed: ssl=0xad568800: I/O error during system call, Connection timed out
,I/qtaguid ( 2272): Tagging socket 33 with tag 1000040100000000{268436481,0} uid 10011, pid: 2272, getuid(): 10011
,I/qtaguid ( 2272): Tagging socket 51 with tag 1000040100000000{268436481,0} uid 10011, pid: 2272, getuid(): 10011
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 61
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  922): [PWL] Off : 1755s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 62
,I/art     (  922): Background partial concurrent mark sweep GC freed 45933(4MB) AllocSpace objects, 202(3MB) LOS objects, 30% free, 35MB/51MB, paused 2.032ms total 195.381ms
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :8
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  922): Plugged
,I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryService(  922): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  922): !@Sync 63
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  922): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,I/ActivityManager(  922): Killing 7841:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1800s
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,I/ActivityManager(  922): Killing 7743:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7727:com.android.chrome/u0a87 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 6463:com.sec.chaton/u0a85 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7712:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7684:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7075:com.osp.app.signin/u0a44 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7053:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7666:com.sec.android.soagent/u0a36 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7643:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager(  922): Killing 7628:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7612:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7587:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 6202:com.google.android.music:main/u0a125 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7038:com.sec.pcw.device/1000 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7143:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1800s
,I/ActivityManager(  922): Killing 7501:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1804s
I/ActivityManager(  922): Killing 7486:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1804s
,I/ActivityManager(  922): Killing 7451:com.samsung.helphub/1000 (adj 15): empty for 1804s
,I/ActivityManager(  922): Killing 7435:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1804s
I/ActivityManager(  922): Killing 7418:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1805s
,I/ActivityManager(  922): Killing 7399:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1805s
,I/ActivityManager(  922): Killing 7384:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1805s
,I/ActivityManager(  922): Killing 7371:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1805s
,I/ActivityManager(  922): Killing 7308:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1805s
,I/ActivityManager(  922): Killing 7332:com.vlingo.midas/u0a32 (adj 15): empty for 1805s
I/ActivityManager(  922): Killing 7265:com.google.android.apps.docs/u0a97 (adj 15): empty for 1806s
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  922): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  922): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  922): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  922): stay LED for fully charged
,D/SSRM:m  (  922): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ActivityManager(  922): Killing 6010:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1807s
,I/ActivityManager(  922): Killing 7241:com.sec.android.app.soundalive/u0a57 (adj 15): empty for 1807s
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/BatteryService(  922): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3222): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3222): Disconnected process message: 10
,D/MotionRecognitionService(  922):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  922): Plugged
I/MotionRecognitionService(  922): setPowerConnected  = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7612/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10018/pid_7643/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10087/pid_7727/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10085/pid_6463/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10097/pid_7265/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10057/pid_7241/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10010/pid_7628/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10077/pid_7143/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10137/pid_7841/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10127/pid_7743/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10098/pid_7308/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10169/pid_7501/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10165/pid_7486/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7712/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10111/pid_7418/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10117/pid_7435/cgroup.procs: No such file or directory
W/libprocessgroup(  922): failed to open /acct/uid_10070/pid_7684/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7053/cgroup.procs: No such file or directory
W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7451/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10036/pid_7666/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10032/pid_7332/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_6010/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10019/pid_7371/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7399/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10002/pid_7587/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10003/pid_7384/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_1000/pid_7038/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10125/pid_6202/cgroup.procs: No such file or directory
,W/libprocessgroup(  922): failed to open /acct/uid_10044/pid_7075/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  288): DCD ON
E/SMD     (  288): DCD ON
D/AndroidRuntime( 8246): 
D/AndroidRuntime( 8246): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8246): CheckJNI is OFF
D/AndroidRuntime( 8246): setted country_code = Poland
D/AndroidRuntime( 8246): setted countryiso_code = PL
D/AndroidRuntime( 8246): setted sales_code = XEO
D/AndroidRuntime( 8246): readGMSProperty: start
D/AndroidRuntime( 8246): readGMSProperty: already setted!!
D/AndroidRuntime( 8246): readGMSProperty: end
D/AndroidRuntime( 8246): addProductProperty: start
E/AffinityControl( 8246): AffinityControl: registerfunction enter
D/AndroidRuntime( 8246): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  922): START PACKAGE DELETE: observer{942933000}
D/PackageManager(  922): pkg{<packageName>}
D/PackageManager(  922): user{0}
D/PackageManager(  922): caller{2000}
D/PackageManager(  922): flags{3}
D/PersonaManagerService(  922): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  922): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  922): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  922): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  922): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  922): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  922): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  922): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  922): getApplicationUninstallationEnabled
D/ApplicationPolicy(  922): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  922): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  922): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  922): Killing 7186:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  922):   Force finishing activity ActivityRecord{12dbac0 u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  922): mDVFSHelper.acquire()
W/PackageSettings(  922): Skipping PackageSetting{3147b951 com.example.hello/10357} due to missing metadata
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/FocusedStackFrame(  922): Set to : 0
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/ActivityManager(  922): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/WifiService(  922): Client connection lost with reason: 4
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 19
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 19
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/art     ( 1715): Explicit concurrent mark sweep GC freed 33793(2014KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 459us total 34.056ms
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     ( 2478): Explicit concurrent mark sweep GC freed 38675(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 21MB/28MB, paused 2.801ms total 61.102ms
D/ConnectivityService(  922): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 6283): Explicit concurrent mark sweep GC freed 35795(1894KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 379us total 35.641ms
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  922): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1829): mOCRHelper is null
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 2272): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/Zygote  ( 8274): MountEmulatedStorage()
I/libpersona( 8274): KNOX_SDCARD checking this for 10018
E/Zygote  ( 8274): v2
I/libpersona( 8274): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8274 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
E/libprocessgroup(  922): failed to kill 1 processes for processgroup 7186
I/SELinux ( 8274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  922): uri = 14 selection = getSealedState
D/SecContentProvider2(  922): mCursor = null
D/SecContentProvider2(  922): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  922): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  922): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 19
W/art     (  922): Suspending all threads took: 6.160ms
D/EnterpriseDeviceManagerService(  922): Package has changed for user 0
D/EnterpriseDeviceManagerService(  922): Admin package name: com.google.android.gms
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3684): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3684): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
D/TimaKeyStoreProvider( 8274): TimaSignature is unavailable
D/ActivityThread( 8274): Added TimaKeyStore provider
I/DBG_DM  ( 3684): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/art     (  922): Explicit concurrent mark sweep GC freed 24654(1950KB) AllocSpace objects, 17(272KB) LOS objects, 30% free, 35MB/51MB, paused 8.607ms total 168.013ms
D/ActivityManager(  922): post active user change for 0
D/KnoxTimeoutHandler(  922): postActiveUserChange for user 0
D/ResourcesManager(  922): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3684): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/art     (  922): WaitForGcToComplete blocked for 95.200ms for cause Explicit
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/SurfaceWidgetView( 1482): destroyHardwareResources():931496431
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
V/WindowOrientationListener(  922): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  922): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  922): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  922): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  922): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/Launcher( 1482): onRestart, Launcher: 632491912
D/Launcher( 1482): onStart, Launcher: 632491912
D/Launcher.HomeView( 1482): onStart
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1941): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1941): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager( 8274): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SecContentProvider2(  922): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  922): mCursor = null
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/RegisteredServicesCache( 1458): empty dynamic service
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityThread( 3684): Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3684): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3684): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 3684): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 3684): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 3684): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 3684): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3684): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3684): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3684): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3684): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3684): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3684): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/Launcher.HomeView( 1482): onStop
D/InputMethodManagerService(  922): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/Timeline( 3684): Timeline: Activity_idle id: android.os.BinderProxy@2dbb5cb2 time:1922993
I/ActivityManager(  922): Activity reported stop, but no longer stopping: ActivityRecord{30f6b189 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t3}
W/ContextImpl(  922): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/StatusBarManagerService(  922): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/InputMethodManagerService(  922): Got RemoteException sending setActive(false) notification to pid 7186 uid 10356
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/KLMS-2.4.503: ( 8274): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/KLMS-2.4.503: ( 8274): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450737945425
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/KLMS-2.4.503: ( 8274): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8274): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ActivityManager(  922): mDVFSHelper.release()
I/Timeline(  922): Timeline: Activity_windows_visible id: ActivityRecord{221a58c5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1923068
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8296): MountEmulatedStorage()
E/Zygote  ( 8296): v2
I/libpersona( 8296): KNOX_SDCARD checking this for 10103
I/libpersona( 8296): KNOX_SDCARD not a persona
I/ActivityManager(  922): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8296 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  922): Killing 7857:com.android.email/u0a162 (adj 15): empty for 1809s
D/RCPManagerService(  922): PackageReceiver onReceive()
I/HarmonyEASService(  922): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/KnoxMUMContainerPolicy(  922): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  922): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  922): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  922): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  922): uID is 10356
V/EnterpriseBillingPolicy(  922): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  922): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  922): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  922): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  922): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  922): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  922): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/SELinux ( 8296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TaskPersister(  922): removeObsoleteFile: deleting file=4_task.xml
D/KnoxTimeoutHandler(  922): handleActiveUserChange for user 0
D/TaskPersister(  922): removeObsoleteFile: deleting file=3_task.xml
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 8296): TimaSignature is unavailable
D/ActivityThread( 8296): Added TimaKeyStore provider
W/libprocessgroup(  922): failed to open /acct/uid_10162/pid_7857/cgroup.procs: No such file or directory
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 8296): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  922): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  922): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  922): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/art     (  922): Explicit concurrent mark sweep GC freed 14260(813KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 35MB/51MB, paused 2.842ms total 292.792ms
D/elm:14451( 8296): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8296): ELMEngine.ELMEngine( context ).
D/elm:14451( 8296): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8296): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8296): ElmAgentService : onCreate()
D/elm:14451( 8296): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8296): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8296): MDMBridge.getInstance()
D/elm:14451( 8296): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8296): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8312): MountEmulatedStorage()
E/Zygote  ( 8312): v2
I/libpersona( 8312): KNOX_SDCARD checking this for 10016
I/libpersona( 8312): KNOX_SDCARD not a persona
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager(  922): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8312 uid=10016 gids={50016, 9997} abi=armeabi-v7a
I/art     (  317): Explicit concurrent mark sweep GC freed 8719(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 11.154ms
D/PackageManager(  922): delete codoeFile: 
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.233ms
D/PackageManager(  922): result of delete: 1{942933000}
I/art     ( 1181): Explicit concurrent mark sweep GC freed 112534(5MB) AllocSpace objects, 6(312KB) LOS objects, 30% free, 36MB/52MB, paused 574us total 87.983ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.648ms
I/SELinux ( 8312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 8246): Shutting down VM
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1181): Icon Only
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): There is/are notification(s) 
D/ResourcesManager(  922): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14451( 8296): ElmAgentService : onDestroy().
I/ActivityManager(  922): Killing 7547:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1809s
D/TimaKeyStoreProvider( 8312): TimaSignature is unavailable
D/ActivityThread( 8312): Added TimaKeyStore provider
D/ResourcesManager(  922): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 8312): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  922): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8312): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8312): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8312): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager(  922): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  922): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  922): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
